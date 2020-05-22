# Regex

## Context

1. What is a regex? Language for describing *regular* text
    - bigger than python, but python-flavored
    - **regex** *matches* a piece of text, the **subject**
1. `re.findall(regexp, subject)`, `re.search(regexp, subject)`
1. Demo
1. `re.search`, `re.findall`, (`re.sub` later)
1. `hlre`
1. Regex Parts (see below)
1. `re.sub` + capture groups
1. pandas methods, `pd.Series.str` -- `.contains`, `.count`, `.extract`, `.replace`

## Parts of Regular Expressions

1. literals
1. metachars, char classes: `.`, `\w`, `\s`, `\d` (+ caps variants)
1. repeating `*`, `+`, `{m[,[n]]}`, `?`
1. any/none of `[]`
1. anchors, `^` + `$`, `\b`
1. capture groups, group referencing