# IlanaORM Documentation

This is the official documentation website for IlanaORM, built with [Mintlify](https://mintlify.com).

## Development

To run the documentation locally:

```bash
# Install dependencies
npm install

# Start development server
npm run dev
```

The documentation will be available at `http://localhost:3000`.

## Structure

- `mint.json` - Mintlify configuration
- `introduction.mdx` - Homepage content
- `quickstart.mdx` - Getting started guide
- `essentials/` - Core concepts and guides
- `database/` - Database management guides (migrations, seeders, factories, connections, transactions)
- `advanced/` - Advanced features (events, observers, casting, scopes)
- `api-reference/` - API documentation

## Customization

### Colors and Branding

Edit `mint.json` to customize:
- Colors (`colors` section)
- Logo (`logo` section)
- Navigation (`navigation` section)
- Footer links (`footerSocials` section)

### Content

All content is written in MDX (Markdown with React components). You can:
- Edit existing pages
- Add new pages (remember to update `mint.json` navigation)
- Use Mintlify components like `<Card>`, `<CodeGroup>`, `<Tip>`, etc.

### Deployment

The documentation can be deployed to:
- Mintlify hosting (recommended)
- Vercel
- Netlify
- Any static hosting service

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally with `npm run dev`
5. Submit a pull request

## License

This documentation is licensed under MIT License.