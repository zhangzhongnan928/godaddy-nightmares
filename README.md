# Plan for GitHub Repository: Documenting Domain Auction Issues

This document outlines the structure and essential files for a GitHub repository dedicated to collecting user experiences, particularly negative ones, with GoDaddy Auctions and potentially other domain auction platforms.

**1. Repository Name Suggestion:**

* `domain-auction-experiences`
* `godaddy-auction-issues`
* `auctioned-domain-nightmares`

**2. Core Files:**

* **`README.md`:**
    * **Purpose:** Clearly state the repository's goal: to serve as a public archive of user-submitted experiences with domain auction platforms (initially focusing on GoDaddy Auctions) to raise awareness about potential pitfalls like failed transfers, sales of non-owned domains, poor customer support, and fund holding issues.
    * **Motivation:** Briefly mention the experience documented in the blog post ([Link to Blog Post/Your Story Here]) as the catalyst.
    * **How to Contribute:** Explain the primary method(s) for submission (e.g., opening a GitHub Issue using the provided template, submitting a Pull Request with a Markdown file). Link clearly to `CONTRIBUTING.md`.
    * **Disclaimer:** Include a disclaimer stating that this is a community effort, not affiliated with any company, stories represent individual accounts, and readers should perform their own due diligence.
    * **Privacy Warning:** Emphasize that contributors MUST redact all Personal Identifiable Information (PII).
    * **Code of Conduct:** Link to `CODE_OF_CONDUCT.md`.
    * **License:** Link to `LICENSE`.

* **`CONTRIBUTING.md`:**
    * **Welcome:** Thank potential contributors.
    * **Submission Methods:**
        * **GitHub Issues (Recommended):** Detail how to open a new issue using the "Share Your Experience" template. Stress the importance of filling out all sections and *removing PII*.
        * **Pull Requests (Optional):** For those comfortable with Git, explain how to fork the repo, create a Markdown file for their story (e.g., in a `/stories` directory using a `YYYY-MM-DD-platform-summary.md` naming convention), write the story following the template, ensure *no PII* is included, and submit a PR.
    * **Story Guidelines/Template:** Provide structure for submissions:
        * Platform: (e.g., GoDaddy Auctions)
        * Date(s) of Incident:
        * Domain Involved: (Optional - advise anonymizing if preferred, e.g., `domain-name.tld`)
        * Amount Involved: (Optional - approximate range might be safer than exact figures)
        * Summary of Issue:
        * Timeline of Events:
        * Support Interaction Summary:
        * Resolution (or Lack Thereof):
        * Key Takeaway/Warning for Others:
    * **Anonymity & PII:** Dedicate a prominent section explicitly warning against including names, contact info, exact order numbers, specific financial details, or any other PII. Explain *why* (public visibility).
    * **Evidence:** State that direct uploads of private documents are not allowed. Contributors can *describe* evidence they possess but should not link or upload private files.
    * **Review:** Briefly mention that submissions might be lightly reviewed for PII and adherence to the Code of Conduct before merging (if using PRs) or tagging (if using Issues).

* **`CODE_OF_CONDUCT.md`:**
    * Adopt a standard Code of Conduct (like the Contributor Covenant). This ensures respectful interactions within the repository's issues and discussions.

* **`LICENSE`:**
    * Specify a license. A good combination could be:
        * **MIT License:** For the repository structure, templates, and any code.
        * **Creative Commons Attribution 4.0 International (CC BY 4.0):** For the *content* of the submitted stories. This allows others to share and adapt the stories as long as they give attribution, which aligns with the goal of raising awareness. Contributors would need to agree to this license upon submission (e.g., via a checkbox in the issue template).

**3. GitHub Features:**

* **Issue Templates (`.github/ISSUE_TEMPLATE/share-experience.md`):**
    * Create a structured template for submitting stories via GitHub Issues.
    * Include fields based on the Story Guidelines in `CONTRIBUTING.md`.
    * Use Markdown frontmatter to automatically assign labels (e.g., `user-story`, `godaddy-auctions`).
    * **Crucially, include checkboxes:**
        * `[ ] I have read and agree to the CODE_OF_CONDUCT.md`
        * `[ ] I have read CONTRIBUTING.md, especially the section on PII.`
        * `[ ] I confirm that I have removed ALL Personal Identifiable Information (PII) from my submission.`
        * `[ ] I agree to license my contribution under the CC BY 4.0 license.`

* **Labels:** Use labels to categorize issues (e.g., `godaddy-auctions`, `namecheap-auctions`, `failed-transfer`, `support-issue`, `non-owned-domain`, `resolved`, `unresolved`).

**4. Initial Content:**

* Add your own story (from the blog post, carefully redacting any remaining PII like specific customer numbers if not already done) as the first entry (either as an Issue or a Markdown file).

**Next Steps:**

1.  Create a new public repository on GitHub.
2.  Create the `README.md`, `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, and `LICENSE` files based on the outlines above.
3.  Set up the Issue Template in the `.github/ISSUE_TEMPLATE/` directory.
4.  Add your story as the first example.
5.  Share the link to the repository (e.g., in your blog post, on relevant forums) to invite contributions.
