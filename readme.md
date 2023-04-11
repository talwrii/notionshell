# notionshell

Another partially-implemented [notion](https://www.notion.so/) command line client.

* Not feature complete, *partially implemented*
* Uses official notion library
* Patches welcome
* "Highish" level - not just a close wrapper around the api
* Still fairly general

Hopefully this is quite easy to extend.

# Usage

* List databases: `notionshell database list`
* Get page in a database: `notionshell database pages $ID`

# Authetication

1. Follow instructions [here](https://www.notion.so/help/create-integrations-with-the-notion-api) to create an integration.
1. Grant integration access to databases (see above)
1. Set `NOTION_API_KEY` environment variable to integration token

# Prior work

* Notion is broadly used proprietary software. There are open source alternatives such as org-mode for emacs, wikis such as mediawiki, or similar clients like obsidian or logseq. Similar propietary tools include roam research and at a stretch blogging tools like wordpress, medium or substack.
* [notions](https://pypi.org/project/notions/) Could upload pages or block, was not using notion library
* [notion-cli](https://github.com/fieldflat/notion-cli-py) Could not list databases, was not using notion library
* [clotion](https://github.com/psych0der/clotion) In typescript, no stars on github at time of writing
* There are various notion libraries for different languages
* There is an HTTP client that is quite usable.

# Upcoming work

* Features as I use them
* One day I'll create something to sync emacs org-mode to notion
