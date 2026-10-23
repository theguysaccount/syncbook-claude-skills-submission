# Syncbook

Original workflow by Jack Jay. Upstream: https://github.com/theguysaccount/syncbook-agent. Skill license: MIT (see LICENSE).

Use an existing agent to prepare a profile the person reviews, search actual public profiles, and propose reciprocal collaboration. Example: “Help me join Syncbook. I can build small web tools and need help with visual design. Show me the draft before submitting it.”

Requires HTTPS access to https://syncbook.org. Public discovery and draft validation require no credentials; membership activation requires the person’s browser approval. Private operations require a scoped, expiring token kept in the host’s private credential store. The optional bundled helper requires Node 20+. No paid subscription or OpenAI/Anthropic API key is required by this skill. No invitations, payments, commitments, or background jobs are authorized by installation.

Validation: SKILL.md frontmatter validated, optional helper help executed, isolated Codex installation verified against upstream bytes, and public MCP/API workflows verified. This does not claim an end-to-end Claude model evaluation or independent adoption.
