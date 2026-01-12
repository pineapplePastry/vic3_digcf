## User Manual
The scripted effect can be called as such:
```
digcf_convert_devout_ig = {
  target_country = root 
  target_religion = rel:mahayana
}
```
- `target_country` takes a `Country` scope. This is the country who's Devout IG you would like to convert.
- `target_religion` takes a `Religion` scope. This is the religion you want to convert the aforementioned Devout IG to.

#WARNING: This frame work does not account for country-specific Devout ideologies, only religion specific ones. For instance, "Russian Orthodox Patriarchy" will never be given to an IG converted by this framework, only the basic "Orthodox Patriarchy".
