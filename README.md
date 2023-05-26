# English-speaker-friendly Korean companies
Repository to aggregate data about Korean companies that works with English as main language or accepts non-Korean speaking members.

They might or might not have any job opening at the time of viewing, please do the due dilligence yourself. The list also doesn't include the obvious huge company ones like Google or SAP Labs.

### Environment

- Hugo Static Website (Coyote Theme)
- Deployment URL: https://www.english-speaking-korean.company

### How to Contribute

1. Add a new file with the following filepath: `./content/{company-name}.md`
2. Fill the file with a JSON object with the following attributes:
- **draft** (`boolean`, _required_): always set to `false`
- **title** (`string`, _required_): Name of the company
- **homepageUrl** (`string`, _required_): Homepage URL of the company
- **field** (`string`, _required_): Comma-separated string of the field the company is focusing on.
- **english** (`string`, _required_): input `main` if the company is using English as their main language and `partial` if they simply accepts non-Korean speaking members
- **linkedinUrl** (`string`, _optional_): The URL for the company's LinkedIn Page
- **careerUrl** (`string`, _optional_): The URL for the company's Career Page

3. Create a PR to the `main` branch

Feel free to add more data based on your knowledge and/or experience. Let's empower each other as international software engineers in Korea!


### TODO

- Automatically Append Tags from other attributes of JSON
- Add Hiring status
- Add Tech stack of the company as attribute
- Include other attributes (especially fields) for search criteria (so far only title is searchable)
- SEO
- UI improvement (idea please)
