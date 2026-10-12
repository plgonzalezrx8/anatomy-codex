# Anatomy for Codex

A Codex skills plugin for building detailed interactive isometric SVG explainers, packaged by Pedro Gonzalez from **[Anatomy by Ryan (@wheresryan22)](https://github.com/wheresryan22/anatomy)**. Ryan is the original creator; the original MIT copyright and license are preserved verbatim.

## Use

Enable the Anatomy plugin in Codex, select its Anatomy skill, and describe the technical idea you want to explain. For example: "Explain how a pin tumbler lock opens as an interactive isometric figure."

The package includes all eight examples, the SVG/WebGL/3D geometry kit, React helpers, reference guides and verification scripts. It uses teal instrument icons with light and dark variants. The original standalone skill is independent of this package.

Standalone builds need Node.js 20.10+; browser checks need Chrome or Chromium. React output uses an existing React project. Nothing needs to be installed from npm for standalone builds. Generated work belongs in your project, not in the installed plugin directory; see [the skill](skills/anatomy/SKILL.md#using-the-packaged-skill).

The plugin adds no MCP server, credentials, background service or network permissions. To stop using it, disable or uninstall the plugin through the host's plugin controls; existing generated figures remain ordinary local files.

## Attribution

Original skill and toolkit: [Anatomy by Ryan (@wheresryan22)](https://github.com/wheresryan22/anatomy), copyright 2026 Ryan, MIT licensed. The [MIT license](LICENSE) and original documentation remain included. This package changes only Codex packaging, presentation and installation-path guidance; toolkit and example code are preserved.
