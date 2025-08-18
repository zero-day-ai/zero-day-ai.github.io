# zero-day.ai

AI Security Research & Open Source Tools

## Overview

zero-day.ai is a platform dedicated to advancing AI security through cutting-edge research and open source tools. We focus on understanding, identifying, and mitigating vulnerabilities in AI systems.

## Gibson Framework

Home of **Gibson** - the open source AI model hacking framework for security research.

Gibson provides comprehensive tools for:
- Adversarial attack generation
- Model vulnerability scanning  
- Defense implementation
- Security benchmarking

Visit the [Gibson repository](https://github.com/zero-day-ai/gibson) for more information.

## Website Structure

This site is built with Hugo using a custom terminal-themed design perfect for security research content.

### Directories

- `/content/blog/` - Blog posts and announcements
- `/content/research/` - In-depth security research papers
- `/content/tools/` - Documentation for tools and frameworks
- `/static/` - Static assets (CSS, images, fonts)
- `/layouts/` - Hugo template files
- `/archetypes/` - Content templates

## Local Development

### Prerequisites

- Hugo (v0.41.0 or higher)
- Git

### Running Locally

```bash
# Clone the repository
git clone https://github.com/zero-day-ai/zero-day.ai
cd zero-day.ai

# Start the Hugo development server
hugo server -D

# View the site at http://localhost:1313
```

### Creating New Content

```bash
# Create a new research post
hugo new research/my-research-post.md

# Create a new blog post
hugo new blog/my-blog-post.md
```

## Building for Production

```bash
# Build the static site
hugo

# Output will be in the public/ directory
```

## Configuration

Main configuration is in `theme.toml`. Key settings:
- Site title and subtitle
- Author information
- Social media links
- Terminal prompt customization

## Contributing

We welcome contributions to both the website and the Gibson framework. Please see our contributing guidelines (coming soon).

## License

The website content is licensed under Creative Commons Attribution 4.0.
The Gibson framework is licensed under the MIT License.

## Contact

- GitHub: [github.com/zero-day-ai](https://github.com/zero-day-ai)
- Website: [zero-day.ai](https://zero-day.ai)

---

*Advancing AI security through open research and collaboration*