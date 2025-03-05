# Lightning talks from PyGRAZ Meetup 2025-03-04

This is a collection of notes from thr presentations given and resulting discussions

## Migrating Python projects to uv

Projects using [poetry](https://python-poetry.org/) or classic `requirements.txt` can migrate to [uv](https://docs.astral.sh/uv/) fairly easily by using [migrate-to-uv](https://github.com/mkniewallner/migrate-to-uv).

Uv is the current "new hotness" in the never-ending stream of semi-working packaging solutions for Python projects. It is more performant thanks to an implementation in [rust](https://www.rust-lang.org/), enables to run Python tools without manually setting up a virual environment using `uvx`, honors the `pyproject.toml`, and optionally can install a Python interpreter all by itself.

## Python related and local events

Python:

- [PyCon Austria](https://pycon.pyug.at/), 6th and 7th of April 2025, in Eisenstadt
- [EuroPython 2025](https://ep2025.europython.eu/), from 14th to 20th of July in Prague. The [videos of last year's conference](https://www.youtube.com/playlist?list=PL8uoeex94UhE1CbtkDK4hevp2lBif57Nq) are still available.

Local and somewhat related:

- [Elevate festival](https://elevate.at/) from 5th to 9th of March. Traditionally a highlight is the [Netzpolitischer Abend](https://elevate.at/de/diskurs/programm/e25netpolicyevening/). People who want to dig deeper into "Netzpolitik" might also be interested in the [Logbuch Netzpolitik](https://logbuch-netzpolitik.de/) podcast or various talks from the [Chaos Communication Congress](https://media.ccc.de/).
- [Linuxtage](https://www.linuxtage.at/), on 26th of April at TU Graz, Campus Inffeldgasse
- [Barcamp Graz](https://barcamp-graz.org/), on 17th of May at the FH Joanneum. This is an "un-conference" with a broad set of topics. Quote:
  > What topics will be covered is up to you!
  >
  > On the day of the event, the program will be created collaboratively on-site. All attendees can contribute to up to 7 parallel sessions. If you would like to give talks, workshops, discussions or presentations, you can prepare something in advance or spontaneously suggest a topic. Be sure to be on time to secure a spot on the schedule! You can then simply choose the sessions you want to attend.
- [events.graz.social](https://events.graz.social/), a general register of local events with strong ties to the [Fediverse](https://en.wikipedia.org/wiki/Fediverse).
