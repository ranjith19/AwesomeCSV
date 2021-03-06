# Awesome CSV [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

CSV remains the most futuristic data format from the distant past.

XML has risen and fallen. JSON is just a flash in the pan. YAML is a poisoned chalice. **CSV will outlast them all.**

When the final cockroach breathes her last breath, her dying act will be to scratch her date of death in a CSV file for posterity.


## Contents

- [Awesome CSV Tools](#awesome-csv-tools)
  - [Repair or Validate CSV](#repair-or-validate-csv)
  - [Treat CSV as SQL](#treat-csv-as-sql)
  - [Convert to or from CSV](#convert-to-or-from-csv)
  - [CSV <-> JSON](#csv---json)
- [Awesome CSV Essays](#awesome-csv-essays)
- [Awesome Data in CSV](#awesome-data-in-csv)
- [Awesome Conferences About CSV](#awesome-conferences-about-csv)
- [Awesome CSV Standards](#awesome-csv-standards)
- [META: Other Lists of CSV Tools and References](#meta-other-lists-of-csv-tools-and-references)
- [Code of Conduct](#code-of-conduct)
- [Contributing](#contributing)
- [Footnotes](#footnotes)
- [License](#license)



Here are some awesome tools for dealing with CSV:

## Awesome CSV Tools

- [NimbleText/Live](https://NimbleText.com/Live)<sup><a href='#footnote1'><strong>*</strong></a></sup> - Use patterns to manipulate CSV; the world's simplest code generator.
- [PapaParse](https://www.papaparse.com) - A powerful in-browser CSV parser.
- [d3-dsv](https://github.com/d3/d3-dsv) - d3.js parser and formatter module for delimiter-separated values.
- [CSVKit](http://csvkit.readthedocs.org/en/0.7.3/) - CSV utilities that includes csvsql / csvgrep / csvstat and more.
- [XSV](https://github.com/BurntSushi/xsv) - A fast CSV command-line toolkit written in Rust.
- [sed (gnu tool)](https://www.gnu.org/software/sed/manual/sed.html) - Stream editor.
- [gawk (gnu tool)](https://www.gnu.org/software/gawk/manual/gawk.html) - Text processing and data extraction using [awk](http://pubs.opengroup.org/onlinepubs/009695399/utilities/awk.html).
- [awk by example](https://github.com/learnbyexample/Command-line-text-processing/blob/master/gnu_awk.md#default-field-separation) - Comprehensive examples of using awk.
- [Miller](http://johnkerl.org/miller/doc/) - Like sed / awk / cut / join / sort etc for name-indexed data such as CSV.
- [ParaText](http://www.wise.io/tech/paratext) - CSV parsing at 2.5 GB per second.
- [CSVGet](http://github.com/fizx/csvget/tree/master) - Get structured data from sites as CSV.
- [CSVfix](https://code.google.com/p/csvfix/) - A tool for manipulating CSV data.
- [StreamingPivot](http://streamingpivot.com/) - Pivot and visualize CSV data purely in the browser.
- [Tad](https://www.tadviewer.com) - A fast free cross-platform CSV viewer.
- [Nvd3-tags](http://blog.tryolabs.com/2015/02/27/nvd3-tags-a-tiny-library-for-making-charts-from-csv-data/) - A tiny library for making charts from csv data.
- [Powershell: Import-CSV](https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.utility/import-csv) - Powerful in-built facility for dealing with CSV ([example](https://gist.github.com/dfinke/786ba9edae1b0265ada10b36a7a11ba9)).
- [CSV Tools](https://onlinecsvtools.com/) - A collection of useful CSV utilities.
- [graph-cli](https://github.com/mcastorina/graph-cli) - Flexible command line tool to create graphs from CSV data.
- [CSV to SQL](http://www.convertcsv.com/csv-to-sql.htm) - Online tool to create insert/update/delete etc from CSV data.
- [C#: kbCSV](https://github.com/kentcb/KBCsv/blob/master/README.md) - An efficient, easy to use .NET parsing and writing library for CSV.
- [csvprintf](https://github.com/archiecobbs/csvprintf) - UNIX command line utility for parsing and formatting output based on CSV files.
- [Mockaroo](https://www.mockaroo.com/) - Random data generator for CSV / JSON / SQL / Excel.
- [Ron's CSV Editor](https://www.ronsplace.eu/products/ronseditor) - Handles big files, does miraculous things. A timeless editor for a timeless format.

### Repair or Validate CSV

- [Csvlint.go](https://github.com/Clever/csvlint) - Command line tool for validating CSV files against RFC 4180.
- [csvstudio](http://www.csvstudio.com) - A smart app to repair syntax errors in very large CSV files.

### Treat CSV as SQL

- [TextQL](http://dinedal.github.io/textql/) - Execute SQL against CSV or TSV.
- [Datasette Facets](https://simonwillison.net/2018/May/20/datasette-facets/) - Faceted browse and a JSON API for any CSV File or SQLite DB.
- [q](https://harelba.github.io/q/) - Text as data.


### Convert to or from CSV

- [CSV to Table](https://github.com/vividvilla/csvtotable) - Convert CSV files to searchable and sortable HTML table.

### CSV <-> JSON

- [Agnes](http://www.secretgeek.net/agnes/twoWay.html)<sup><a href='#footnote2'><strong>**</strong></a></sup> - two way Csv to Json.
- [csv2json](https://www.csvjson.com/csv2json) - online tool to convert your CSV or TSV formatted data to JSON and [vice versa](https://www.csvjson.com/json2csv).
- [csv-to-json](https://mango-is.com/tools/csv-to-json/) - Easy, privacy-friendly and offline-first online csv to json converter.


## Awesome CSV Essays

- [Thinking about CSV](https://blog.datacite.org/thinking-about-csv/) - Martin Fenner.
- [In Praise of CSV](https://usopendata.org/2015/03/10/csv) - Waldo Jaquith.
- [Stop Rolling Your Own CSV Parser!](http://www.secretgeek.net/csv_trouble)<sup><a href='#footnote3'><strong>***</strong></a></sup> - Leon B.
- [So You Want To Write Your Own CSV code?](http://thomasburette.com/blog/2014/05/25/so-you-want-to-write-your-own-CSV-code/) - Thomas Burette.
- [Falsehoods Programmers Believe About CSVs](https://donatstudios.com/Falsehoods-Programmers-Believe-About-CSVs) - Jesse Donat.
- [ASCII Delimited Text - Not CSV or TAB delimited text](https://ronaldduncan.wordpress.com/2009/10/31/text-file-formats-ascii-delimited-text-not-csv-or-tab-delimited-text/) - Ronald Duncan.

## Awesome Data in CSV

- [US Data.gov](https://catalog.data.gov/dataset?res_format=CSV) - 18789+ CSV datasets.
- [Australian Government Open Data](https://data.gov.au/dataset?res_format=CSV) - 2715+ CSV datasets.
- [Reference data in csv](https://datahub.io/collections/reference-data) - Easy-to-use reference data in CSV and JSON formats.
- [awesome-public-datasets](https://github.com/awesomedata/awesome-public-datasets) - A topic-centric list of high-quality open datasets in public domains.

## Awesome Conferences About CSV

- [csv,conf](https://csvconf.com/) - A community conference for data makers everywhere.


## Awesome CSV Standards

> The wonderful thing about standards is that there are so many of them to choose from.<br />&mdash;(Possibly) Grace Hopper.

- [RFC 4180](https://tools.ietf.org/html/rfc4180) - "*Common format and MIME Type for Comma-Separated Values (CSV) Files*".
  - [Definition of the CSV Format](https://tools.ietf.org/html/rfc4180#section-2)
  - [MIME Type Registration of text/csv](https://tools.ietf.org/html/rfc4180#section-3)
- [W3C: Model for Tabular Data and Metadata on the Web](https://www.w3.org/TR/tabular-data-model/)
- [CSV Schema Language](http://digital-preservation.github.io/csv-schema/csv-schema-1.2.html) - A language for defining and validating CSV data.
- [csv,specs](https://github.com/csvspecs) - Comma-Separated Values (CSV) Format Specifications (and Tests) incl. CSV v1.0, CSV v1.1, CSV Strict, CSV <3 Numerics, CSV<3 JSON, CSV <3 YAML.

## META: Other Lists of CSV Tools and References

- [structured-text-tools](https://github.com/dbohdan/structured-text-tools) - List of command line tools for manipulating CSV / XML / HTML / JSON / INI etc.
- [META-META](https://raw.githubusercontent.com/secretGeek/AwesomeCSV/master/awesomecsv.csv) - **This list as CSV**.
- [META-META-META](https://nimbletext.com/Live/-971009575/) - A NimbleText pattern that produces this markdown page from this list as a CSV.


## Code of Conduct

See [Code of Conduct](code-of-conduct.md)


## Contributing

See [Contributing](contributing.md)




---

## Footnotes


`*` <span id='footnote1' ></span> I'm the author of [NimbleText](https://NimbleText.com/Live). Of course I put it first on the list. If I didn't personally rate it I wouldn't have spent so much time making and improving it.

`**` <span id='footnote2' ></span> I wrote `agnes` but don't really endorse it for others to use (thus haven't migrated the source code to GitHub). It's slow and non-streaming. I'd go with `papa-parse`. On the plus side, `agnes` has a more comprehensive test suite and simpler api than most.

`***` <span id='footnote3' ></span> Mine too.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Leon Bambrick](http://secretgeek.net) has waived all copyright and related or neighboring rights to this work.
