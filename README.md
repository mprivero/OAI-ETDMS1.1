# OAI-ETDMS1.1
OAI Crosswalk for Electronic Theses and Dissertations Metadata

<b>Purpose</b>

To provide updates to the OAI ETDMS format for the latest version of the ETD-MS v1.1 standard (http://sites.google.com/a/ndltd.org/ndltd/standards/metadata#)

<b>Major Changes</b>

Authors. The <dc.contributor.author> element has been deprecated in v1.1.  The current standard (ETD-MS v1.1) recommends using <dc.creator> to record author names.

Degree Info. The current standard (ETD-MS v1.1) recommends using specialized schema for recording degree information in syntax: thesis.degree.qualifier.  These “degree” elements are now exposed.

<b>Other changes</b>

Formats and Types. A growing practice among repositories is to use qualified type and format elements. This crosswalk includes mapping for qualified elements (e.g. <dc.type.dcmi>)

Descriptions. Non-abstract description data is mapped to <dc.description.note>.

Dates. Only a single date value (date graduated) is outputed.

<b>Acknowledgements</b>
Texas Digital Libraries ETD Metadata Working Group (2015).

