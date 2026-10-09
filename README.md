# R mailing list archives feedback

Public feedback and issue tracker for the [R mailing list archives](https://github.com/r-mailing-lists) and the site that reads them, [r-mailing-lists.thecoatlessprofessor.com](https://r-mailing-lists.thecoatlessprofessor.com/).

The site's source is not public, and the archive repositories are written by scheduled jobs rather than by hand, so this is where everything is tracked: the archives, the data, and the site.

## File an issue

- [Report a bug](https://github.com/r-mailing-lists/feedback/issues/new?template=1-bug.yml) if the site is broken.
- [Report an archive issue](https://github.com/r-mailing-lists/feedback/issues/new?template=2-archive.yml) if a message is missing, garbled, misthreaded, or misdated.
- [Request a feature](https://github.com/r-mailing-lists/feedback/issues/new?template=3-feature.yml) for a new page, view, filter, or export.
- [Propose a list](https://github.com/r-mailing-lists/feedback/issues/new?template=4-list.yml) we should be mirroring but are not.
- [Report a documentation issue](https://github.com/r-mailing-lists/feedback/issues/new?template=5-documentation.yml) if something is wrong, missing, or confusing.
- [Ask a question](https://github.com/r-mailing-lists/feedback/issues/new?template=6-question.yml) about anything else.

## Two things that do not belong here

Security vulnerabilities do not belong in a public tracker. Email support@caffeinatedmath.com instead.

Neither do requests to remove a message or personal information, because filing one would republish the very thing you want taken down. Email support@caffeinatedmath.com, and read the [archive policy](https://github.com/r-mailing-lists/.github/blob/main/ARCHIVE_POLICY.md) first for what to include and what removal here does and does not achieve.

## One thing worth checking first

We mirror the public archives at stat.ethz.ch, one per list, such as [stat.ethz.ch/pipermail/r-help/](https://stat.ethz.ch/pipermail/r-help/). Rcpp-devel and the other R-Forge lists are the exception and come from [R-Forge](https://lists.r-forge.r-project.org/pipermail/). If a message is wrong there too, the problem is in the source and we cannot fix it downstream. Telling us what upstream shows is the single most useful thing a report can include, and the archive issue form has a field for it.

## Links

- [R Mailing Lists](https://r-mailing-lists.thecoatlessprofessor.com/), the site
- [The archives](https://github.com/r-mailing-lists), one repository per list
- [data](https://github.com/r-mailing-lists/data), every list as Parquet
- [rmail-parser](https://github.com/r-mailing-lists/rmail-parser), the parser behind them
