---
name: seo-meta-pack-generator
description: Generate complete SEO meta packs for blog posts. Takes blog content (pasted text, Google Doc URL, file upload, or blog URL) and outputs blog title, URL slug, H1, OG title & description, social media copy (Twitter/LinkedIn/Facebook), JSON-LD schema markup, 5 primary keywords, and 5 secondary keywords. Outputs both chat summary and downloadable spreadsheet. Use this whenever creating new blog content or optimizing existing content for SEO across multiple clients.
compatibility: Google Drive connector (optional), file upload, URL fetch
---

# SEO Meta Pack Generator

Generates complete SEO-optimized meta information packs for blog posts in a single pass.

## What This Does

Takes any blog content and generates:
- **Blog Title** - SEO-optimized, 50-60 characters
- **URL Slug** - Clean, keyword-friendly URL
- **H1 Tag** - Main heading optimized for search
- **OG Title** - Social sharing title (55-65 chars)
- **OG Description** - Meta description (150-160 chars)
- **Twitter Copy** - Tweet-ready copy with hashtags
- **LinkedIn Copy** - Professional network post
- **Facebook Copy** - Engaging social post
- **Schema Markup** - JSON-LD structured data (BlogPosting)
- **5 Primary Keywords** - Main search terms you should target
- **5 Secondary Keywords** - Related long-tail & LSI variations

## How to Use

### Step 1: Provide Content
Paste, upload, or link your blog content:
- **Paste directly**: Raw text or markdown
- **Google Doc**: Shareable link to your Google Doc
- **File upload**: .txt, .md, .docx
- **Blog URL**: Live URL if content is published (reads the page)

### Step 2: (Optional) Specify Intent
- Primary keyword you want to target (if specific)
- Blog category/vertical (optional, for tone)
- Target audience (B2B, B2C, technical, general)

### Step 3: Output
- Chat display of all meta tags + keywords
- Downloadable XLSX spreadsheet ready to share or use in your CMS

---

## Step-by-Step Process

### 1. Parse Content
Extract:
- Main topic/theme
- Key points and subtopics
- Word count and depth
- Any existing keywords mentioned
- Target audience signals

### 2. Generate Blog Title
- 50-60 characters (fits search snippets)
- Include primary keyword naturally
- Benefit-driven or curiosity-driven phrasing
- Avoid clickbait, stay truthful to content

**Template**: `[Primary Keyword]: [Benefit/Angle] [Qualifier if needed]`

Example: `Email Marketing: Complete Guide for 2024`

### 3. Create URL Slug
- All lowercase
- Hyphens between words
- No special characters or stopwords
- 3-5 key words max
- Derived from blog title

Example: `email-marketing-complete-guide-2024`

### 4. Write H1 Tag
- Can be same or slightly different from title
- Should match search intent
- Include primary keyword once naturally
- 8-10 words ideal

Example: `The Complete Email Marketing Guide for 2024`

### 5. OG Title & Description
**OG Title** (55-65 chars):
- Shorter, punchier version of blog title
- Include primary keyword
- Optimized for social click-through

**OG Description** (150-160 chars):
- Summary of post value
- Include 1-2 key benefits
- Call-to-action oriented

### 6. Social Media Copy
Generate 3 variations (one for each platform):

**Twitter** (280 chars max):
- Hook + benefit + link call-to-action
- Add 1-2 relevant hashtags
- Conversational tone

**LinkedIn** (1,300 chars max):
- Professional angle
- Value + credibility
- Thought leadership tone
- Include emoji sparingly

**Facebook** (500 chars max):
- Engaging, personal tone
- Story-like opener
- Question or curiosity hook
- Link preview friendly

### 7. JSON-LD Schema
Generate BlogPosting schema with:
```json
{
  "@context": "https://schema.org",
  "@type": "BlogPosting",
  "headline": "[Blog Title]",
  "description": "[OG Description]",
  "url": "[Full Blog URL]",
  "datePublished": "[Today's Date]",
  "author": {
    "@type": "Organization",
    "name": "[Your Company/Name]"
  },
  "keywords": "[Keywords comma-separated]"
}
```

Copy-paste ready for your blog's <head> section.

### 8. Target Keywords

**5 Primary Keywords** (main search terms to target):
- 1-2 word terms from blog topic
- Extracted from content + topic analysis
- Ranked by relevance to your content
- Include search volume indicator (High/Medium/Low)

Example for "Email Marketing Guide":
1. Email marketing
2. Email marketing guide
3. Email marketing strategy
4. B2B email marketing
5. Email marketing best practices

**5 Secondary Keywords** (related long-tail + LSI):
- Longer, more specific search terms
- Related intent variations
- LSI (Latent Semantic Indexing) keywords
- Lower competition, targeted traffic

Example for same topic:
1. How to create an email marketing campaign
2. Email marketing tips for beginners
3. Email marketing automation tools
4. Effective email marketing techniques
5. Email marketing ROI metrics

Format in spreadsheet: One keyword per row with volume/difficulty notes.

---

## Output Spreadsheet Format

| Field | Value | Notes |
|-------|-------|-------|
| Blog Title | [Generated Title] | 50-60 chars |
| URL Slug | [slug-here] | For CMS |
| H1 Tag | [H1 Heading] | Main heading |
| OG Title | [OG Title] | Social sharing |
| OG Description | [150-160 chars] | Meta description |
| Twitter Copy | [Tweet] | 280 chars max |
| LinkedIn Copy | [Professional post] | Engagement-focused |
| Facebook Copy | [Social post] | Conversational |
| Schema JSON | [JSON-LD code] | Copy to <head> |
| Primary Keyword 1 | [Keyword] | High relevance |
| Primary Keyword 2 | [Keyword] | High relevance |
| Primary Keyword 3 | [Keyword] | High relevance |
| Primary Keyword 4 | [Keyword] | High relevance |
| Primary Keyword 5 | [Keyword] | High relevance |
| Secondary Keyword 1 | [Long-tail keyword] | Related intent |
| Secondary Keyword 2 | [Long-tail keyword] | Related intent |
| Secondary Keyword 3 | [Long-tail keyword] | Related intent |
| Secondary Keyword 4 | [Long-tail keyword] | Related intent |
| Secondary Keyword 5 | [Long-tail keyword] | Related intent |

---

## Tips for Best Results

1. **Content Quality**: Clearer, more detailed blog content = better generated meta
2. **Keyword Intent**: If you know your target keyword, mention it upfront
3. **Audience**: Specify B2B vs B2C for tone/angle adjustments
4. **Length**: Works best with 500+ word posts (more context = better output)
5. **Review & Edit**: Always review generated copy—tweak for your brand voice

---

## Common Tweaks You'll Make

- **Title too long?** Remove qualifier or benefit phrase
- **Keywords not quite right?** Mention the specific keyword you want in your input
- **Social copy too formal?** Ask for more conversational version
- **OG description too generic?** Specify your unique angle upfront

---

## Multi-Client Workflow

1. Create one spreadsheet per client (or add column for client name)
2. Re-run this skill for each blog post
3. Export XLSX, share with client or CMS team
4. Archive in client folder for reference

Tag each row with client name or project for easy sorting.
