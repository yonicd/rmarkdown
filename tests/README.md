Tests and Coverage
================
06 August, 2018 15:25:46

This output is created by
[covrpage](https://github.com/yonicd/covrpage).

## Coverage

Coverage summary is created using the
[covr](https://github.com/r-lib/covr)
package.

| Object                                                         | Coverage (%) |
| :------------------------------------------------------------- | :----------: |
| rmarkdown                                                      |     2.64     |
| [R/base64.R](../R/base64.R)                                    |     0.00     |
| [R/beamer\_presentation.R](../R/beamer_presentation.R)         |     0.00     |
| [R/draft.R](../R/draft.R)                                      |     0.00     |
| [R/github\_document.R](../R/github_document.R)                 |     0.00     |
| [R/html\_document\_base.R](../R/html_document_base.R)          |     0.00     |
| [R/html\_document.R](../R/html_document.R)                     |     0.00     |
| [R/html\_extras.R](../R/html_extras.R)                         |     0.00     |
| [R/html\_fragment.R](../R/html_fragment.R)                     |     0.00     |
| [R/html\_notebook\_output.R](../R/html_notebook_output.R)      |     0.00     |
| [R/html\_notebook.R](../R/html_notebook.R)                     |     0.00     |
| [R/html\_paged.R](../R/html_paged.R)                           |     0.00     |
| [R/html\_resource\_copy.R](../R/html_resource_copy.R)          |     0.00     |
| [R/html\_resources.R](../R/html_resources.R)                   |     0.00     |
| [R/html\_vignette.R](../R/html_vignette.R)                     |     0.00     |
| [R/includes.R](../R/includes.R)                                |     0.00     |
| [R/ioslides\_presentation.R](../R/ioslides_presentation.R)     |     0.00     |
| [R/knit\_print.R](../R/knit_print.R)                           |     0.00     |
| [R/latex\_dependencies.R](../R/latex_dependencies.R)           |     0.00     |
| [R/list\_builder.R](../R/list_builder.R)                       |     0.00     |
| [R/md\_document.R](../R/md_document.R)                         |     0.00     |
| [R/odt\_document.R](../R/odt_document.R)                       |     0.00     |
| [R/output\_format.R](../R/output_format.R)                     |     0.00     |
| [R/pandoc.R](../R/pandoc.R)                                    |     0.00     |
| [R/pdf\_document.R](../R/pdf_document.R)                       |     0.00     |
| [R/performance.R](../R/performance.R)                          |     0.00     |
| [R/powerpoint\_presentation.R](../R/powerpoint_presentation.R) |     0.00     |
| [R/relative\_to.R](../R/relative_to.R)                         |     0.00     |
| [R/render\_html.R](../R/render_html.R)                         |     0.00     |
| [R/render\_site.R](../R/render_site.R)                         |     0.00     |
| [R/render.R](../R/render.R)                                    |     0.00     |
| [R/rtf\_document.R](../R/rtf_document.R)                       |     0.00     |
| [R/shiny\_prerendered.R](../R/shiny_prerendered.R)             |     0.00     |
| [R/shiny.R](../R/shiny.R)                                      |     0.00     |
| [R/slidy\_presentation.R](../R/slidy_presentation.R)           |     0.00     |
| [R/stack.R](../R/stack.R)                                      |     0.00     |
| [R/tufte\_handout.R](../R/tufte_handout.R)                     |     0.00     |
| [R/word\_document.R](../R/word_document.R)                     |     0.00     |
| [R/zzz.R](../R/zzz.R)                                          |     0.00     |
| [R/util.R](../R/util.R)                                        |     2.54     |
| [R/params.R](../R/params.R)                                    |    14.89     |
| [R/html\_dependencies.R](../R/html_dependencies.R)             |    23.08     |
| [R/html\_parser.R](../R/html_parser.R)                         |    95.74     |

<br>

## Unit Tests

Unit Test summary is created using the
[testthat](https://github.com/r-lib/testthat)
package.

|                      | file                                                  |  n |  time | error | failed | skipped | warning |
| -------------------- | :---------------------------------------------------- | -: | ----: | ----: | -----: | ------: | ------: |
| test-dependencies.R  | [test-dependencies.R](testthat/test-dependencies.R)   | 10 | 0.058 |     0 |      0 |       0 |       0 |
| test-encode-decode.R | [test-encode-decode.R](testthat/test-encode-decode.R) |  1 | 0.003 |     0 |      0 |       0 |       0 |
| test-formats.R       | [test-formats.R](testthat/test-formats.R)             |  3 | 0.003 |     0 |      0 |       3 |       0 |
| test-htmlparse.R     | [test-htmlparse.R](testthat/test-htmlparse.R)         |  4 | 0.020 |     0 |      0 |       0 |       0 |
| test-ioslides.R      | [test-ioslides.R](testthat/test-ioslides.R)           |  2 | 0.002 |     0 |      0 |       2 |       0 |
| test-notebook.R      | [test-notebook.R](testthat/test-notebook.R)           |  2 | 0.002 |     0 |      0 |       2 |       0 |
| test-params.R        | [test-params.R](testthat/test-params.R)               | 13 | 0.017 |     0 |      0 |       3 |       0 |
| test-resources.R     | [test-resources.R](testthat/test-resources.R)         | 14 | 0.015 |     0 |      0 |      14 |       0 |
| test-site.R          | [test-site.R](testthat/test-site.R)                   |  1 | 0.001 |     0 |      0 |       1 |       0 |

<details open>

<summary> Show Detailed Test Results
</summary>

| file                                                        | context            | test                                                                      | status  |  n |  time |
| :---------------------------------------------------------- | :----------------- | :------------------------------------------------------------------------ | :------ | -: | ----: |
| [test-dependencies.R](testthat/test-dependencies.R#L27_L41) | dependencies       | dependency merge is correct                                               | PASS    | 10 | 0.058 |
| [test-encode-decode.R](testthat/test-encode-decode.R#L7)    | encoding           | R objects can be encoded, decoded                                         | PASS    |  1 | 0.003 |
| [test-formats.R](testthat/test-formats.R#L5)                | formats            | formats successfully produce a document                                   | SKIPPED |  1 | 0.001 |
| [test-formats.R](testthat/test-formats.R#L36)               | formats            | documents with spaces in names can be rendered                            | SKIPPED |  1 | 0.001 |
| [test-formats.R](testthat/test-formats.R#L63)               | formats            | setting theme, highlight or fig\_retina yields an error on html\_vignette | SKIPPED |  1 | 0.001 |
| [test-htmlparse.R](testthat/test-htmlparse.R#L21_L25)       | HTML parsing       | different attribute quoting styles are supported                          | PASS    |  1 | 0.005 |
| [test-htmlparse.R](testthat/test-htmlparse.R#L35_L39)       | HTML parsing       | irrelevant white space is ignored                                         | PASS    |  1 | 0.004 |
| [test-htmlparse.R](testthat/test-htmlparse.R#L56_L60)       | HTML parsing       | common resource types are found in a simple document                      | PASS    |  1 | 0.006 |
| [test-htmlparse.R](testthat/test-htmlparse.R#L72_L76)       | HTML parsing       | resources referenced in CSS files are discovered                          | PASS    |  1 | 0.005 |
| [test-ioslides.R](testthat/test-ioslides.R#L56)             | ioslides           | test\_ioslides\_presentation                                              | SKIPPED |  1 | 0.001 |
| [test-ioslides.R](testthat/test-ioslides.R#L132)            | ioslides           | ioslides presentation is styled                                           | SKIPPED |  1 | 0.001 |
| [test-notebook.R](testthat/test-notebook.R#L12)             | notebook           | an example R Notebook document can be rendered and parsed                 | SKIPPED |  1 | 0.001 |
| [test-notebook.R](testthat/test-notebook.R#L38)             | notebook           | a custom output\_source can be used on render                             | SKIPPED |  1 | 0.001 |
| [test-params.R](testthat/test-params.R#L5)                  | params             | setting of params works                                                   | SKIPPED |  1 | 0.001 |
| [test-params.R](testthat/test-params.R#L34)                 | params             | params render their UI                                                    | SKIPPED |  1 | 0.001 |
| [test-params.R](testthat/test-params.R#L63_L64)             | params             | parameters are configurable                                               | PASS    | 10 | 0.014 |
| [test-params.R](testthat/test-params.R#L114)                | params             | params hidden w/o show\_default                                           | SKIPPED |  1 | 0.001 |
| [test-resources.R](testthat/test-resources.R#L5)            | resource discovery | R Markdown resource discovery finds expected resources                    | SKIPPED |  1 | 0.001 |
| [test-resources.R](testthat/test-resources.R#L26)           | resource discovery | HTML resource discovery finds expected resources                          | SKIPPED |  1 | 0.002 |
| [test-resources.R](testthat/test-resources.R#L42)           | resource discovery | Vanilla Markdown resource discovery finds expected resources              | SKIPPED |  1 | 0.001 |
| [test-resources.R](testthat/test-resources.R#L59)           | resource discovery | PDF-specific resources are discovered                                     | SKIPPED |  1 | 0.001 |
| [test-resources.R](testthat/test-resources.R#L75)           | resource discovery | bare relative directory references are ignored                            | SKIPPED |  1 | 0.001 |
| [test-resources.R](testthat/test-resources.R#L83)           | resource discovery | dependencies in .R files are recursively discovered                       | SKIPPED |  1 | 0.001 |
| [test-resources.R](testthat/test-resources.R#L98)           | resource discovery | implicitly discovered directories are ignored                             | SKIPPED |  1 | 0.001 |
| [test-resources.R](testthat/test-resources.R#L113)          | resource discovery | resource\_files use cases all work                                        | SKIPPED |  1 | 0.001 |
| [test-resources.R](testthat/test-resources.R#L128)          | resource discovery | dependencies can be discovered on .R files directly                       | SKIPPED |  1 | 0.001 |
| [test-resources.R](testthat/test-resources.R#L143)          | resource discovery | filenames with shell characters can use relative resource paths           | SKIPPED |  1 | 0.001 |
| [test-resources.R](testthat/test-resources.R#L159)          | resource discovery | resources not deleted when filenames contain shell characters             | SKIPPED |  1 | 0.001 |
| [test-resources.R](testthat/test-resources.R#L172)          | resource discovery | empty quoted strings don’t confuse resource discovery                     | SKIPPED |  1 | 0.001 |
| [test-resources.R](testthat/test-resources.R#L187)          | resource discovery | resources are discovered in CSS files                                     | SKIPPED |  1 | 0.001 |
| [test-resources.R](testthat/test-resources.R#L202)          | resource discovery | resources are discovered in notebook files                                | SKIPPED |  1 | 0.001 |
| [test-site.R](testthat/test-site.R#L5)                      | site               | render\_site                                                              | SKIPPED |  1 | 0.001 |

</details>

<details>

<summary> Session Info </summary>

| Field    | Value                               |
| :------- | :---------------------------------- |
| Version  | R version 3.5.0 (2018-04-23)        |
| Platform | x86\_64-apple-darwin15.6.0 (64-bit) |
| Running  | macOS High Sierra 10.13.5           |
| Language | en\_US                              |
| Timezone | America/New\_York                   |

| Package  | Version |
| :------- | :------ |
| testthat | 2.0.0   |
| covr     | 3.1.0   |
| covrpage | 0.0.5   |

</details>

<!--- Final Status : skipped/warning --->
