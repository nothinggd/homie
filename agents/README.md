\# HOMIE AI TEAM



The AI team is responsible for helping build and maintain Homie.



\## Principles



1\. Do not invent requirements.

2\. Read project documentation before making changes.

3\. Do not modify unrelated features.

4\. Security is required for every feature.

5\. Every feature must be tested.

6\. Production changes require human approval.

7\. Never expose secrets or API keys.

8\. Never delete production data without explicit human approval.

9\. Keep documentation updated.

10\. Prefer simple and maintainable solutions.



\## Human Approval



The AI must ask for human approval before:



\- Deleting production data

\- Performing destructive database migrations

\- Changing production secrets

\- Changing authentication security settings

\- Deploying major production changes

\- Making changes that can cause data loss



\## Development Process



Every feature should follow:



Requirements

→ Design

→ Implementation

→ Testing

→ Security Review

→ Deployment



\## Source of Truth



The following documents are authoritative:



\- docs/PRODUCT.md

\- docs/PRD.md

\- docs/ARCHITECTURE.md

\- docs/DATABASE.md

\- docs/SECURITY.md



If documentation conflicts with an instruction, stop and ask for clarification.



\## Security



Never:



\- Hard-code secrets

\- Commit API keys

\- Expose service-role keys to the client

\- Disable security controls to make a feature work

\- Bypass authentication or authorization



\## Code Quality



Code should be:



\- Simple

\- Readable

\- Maintainable

\- Tested

\- Secure



Avoid unnecessary dependencies and unnecessary complexity.

