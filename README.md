# ThinkPython-fa-IR-Glossary

*[Think Python](http://www.greenteapress.com/thinkpython/) (book by Allen B. Downey) Persian translation glossary*.

## Goals

The goal of this glossary is to create a list of common Persian translation terms to Keep translations of the [main project](https://github.com/itmard/think-python) consistent.

## Translations
Translations are available at https://github.com/ThinkPythonPersian/thinkbook.
If you prefer Markdown, [here](https://github.com/behroozam/persianthinkpython) is the Markdown version

## Viewing the glossary

* [HTML](http://ziaa.github.io/ThinkPython-fa-IR-Glossary/)
* [JSON](http://ziaa.github.io/ThinkPython-fa-IR-Glossary/terms.json)

## Proposing changes and contributing

#### To add a term:

* Review [the existing terms](http://ziaa.github.io/ThinkPython-fa-IR-Glossary/), and if not already listed
  1. Navigate to [_data/terms.yml](_data/terms.yml)
  2. Click `Edit`
  3. Add the new term where appropriate **alphabetically**
  4. Click "Propose change"

This will create a pull request, to which you will be automatically subscribed, and allow the community to weigh on on the merits of your proposed addition.

### Suggest changes to an existing term:

1. Navigate to [_data/terms.yml](_data/terms.yml)
2. Click `Edit`
3. Edit the definition of the term as you feel is appropriate
4. Click "Propose change"

This will create a pull request, to which you will be automatically subscribed, and allow the community to weigh on on the merits of your proposed change.

## Basic structure

Terms are stored in the [_data/terms.yml](_data/terms.yml) as [YAML](http://en.wikipedia.org/wiki/YAML), which is essentially each line containing a term and it's Persian translation, with a single colon separating the two. A term might look like this:

```yml
Statement: دستور
```

Beyond that, the terms are rendered human readable via `index.html` and machine readable via `terms.json`.

## License

ThinkPython-fa-IR-Glossary is licensed under [CC0](LICENSE.md).

## Running locally

1. `script/bootstrap`
2. `script/server`
3. Open [localhost:4000](http://localhost:4000) in your browser

## Special Thanks
Thanks to [benbalter](http://github.com/benbalter), because the main repo forked from http://github.com/benbalter/government-glossary
