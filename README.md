Markdown-based developer diary in [Obsidian](https://obsidian.md/) for my [Master's thesis](https://github.com/orgs/thesis-LMS/repositories).
Using this to track progress, compare methodologies, and document challenges



The default format can be found in `/templates/entry-template.md`.
Creating a new file will create a diary entry under `<today's date>/<today's date, current time>` 
e.g. 13th May 2025/
└──13th May 2025, 10h40

### How to use:
1. Install [Obsidian](https://obsidian.md/download).
2. Create a blank repo with this file structure:
templates/
└── entry-template
3. Make sure to copy and paste the contents of the `entry-template` file!
4. Go to Obsidian Settings -> Community plugins. Search for `Templater` and install it. 
5. Modify Templater's settings:
	- Template folder location: `/templates`
	- Trigger Templater on new file creation: `On`
	- Folder templates:
		- Enable folder templates: `On`
		- `/`  => `/templates/entry-template.md`
> since `/` means global default, any file created in the home directory will be automatically converted to `<today's date>/<today's date, current time>`