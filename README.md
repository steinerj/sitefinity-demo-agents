# Sitefinity Demo Agents

Sample agents for the Sitefinity extensible agent framework.

## Available agents

### [Accessibility Page Editor](./Accessibility-page-editor.md)
Reviews page and content accessibility, including alt text, heading hierarchy, link text, tables, readability, screen-reader concerns, and content that relies too heavily on visual context. It focuses on practical improvements without unnecessary rewriting.

### [Campaign Agent](./Campaign-agent.md)
Creates campaign content directly in Sitefinity from a user brief. It can generate content such as news items and blog posts, inspect the target content type through Sitefinity tools, satisfy required fields, format rich text correctly, and create the resulting items in the CMS.

### [Content Freshness Agent](./content-freshness-agent.md)
Reviews content for time-sensitive claims that may no longer be current or actionable, such as expired dates, stale statistics, superseded policies, temporary arrangements, or outdated organizational information. It distinguishes supported issues from claims that merely need verification and only proposes corrections when evidence supports them.

### [Content Reuse Agent](./Content-reuse-agent.md)
Uses hybrid search to identify duplicated and near-duplicated content across a content estate. It groups similar content into meaningful clusters, compares the actual messaging, highlights meaningful differences, and surfaces opportunities for reusable or centralized business content.

### [Sam Alt-man](./Sam%20Alt-man.md)
Accessibility and alt-text assistant that reviews images and suggests concise, context-aware alternative text following WCAG best practices. It prioritizes accessibility over SEO, avoids unsupported assumptions, and can identify decorative images that should use empty alt text.

### [Gen-Z Agent](./gen-z-agent.md)
A deliberately over-the-top Gen-Z content editor for demo purposes. It reviews formal or corporate copy and suggests savage, meme-aware rewrites using internet slang while preserving the underlying facts, names, dates, numbers, and claims.

## Format

Each agent is stored as a Markdown file containing the instructions for the agent:

```text
agent-name.md
```
