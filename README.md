# ISO_3166-1 French

**Objective:** Provide up-to-date and detailed information in French about ISO_3166_1, i.e. country codes.

**Source:** ISO Online Browsing Platform https://www.iso.org/obp/ui/fr/#home (as of June 22nd, 2017)

**Country object:**
```
{
  "country_code_alpha_2": "FR",
  "country_code_alpha_3": "FRA",
  "name": "France",
  "determiner": "la",
  "long_name": "la République française",
  "local_short_names": [
    {
      "language_code_alpha_2": "fr",
      "language_code_alpha_3": "fra",
      "local_short_name": "France (la)"
    }
  ]
}
```
* `name`: common country name (which does not include a determiner)
* `determiner`: potential determiner for the name
* `long_name`: potential long version of the country name
* `local_short_names`: list of country names in local languages
