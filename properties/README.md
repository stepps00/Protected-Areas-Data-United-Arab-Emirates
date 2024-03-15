# Protected-Areas-Data-United-Arab-Emirates Properties

- `id`: A unique feature identifier. Integer value.
	- _Example: 24_

- `name`: The name of the protected area. Typically in English, formatted using the name and type together. String value.
	- _Example: "Bridge Lake Outwash Plain Forest Conservation Reserve"_

- `namealt`: Alternative names of the protected area, when available. When multiple alternative names are present, names are separated by a semi-colon and space. String value.
	- _Example: "Imam Sahib Wildlife Reserve; Imam Sahib (Kunduz) Wildlife Reserve"_

- `nameloc`: The name of the protected area, in a local language (see `langloc` value), formatted using the name and type together. String value.
	- _Example: "三陸復興国立公園"_

- `namelocalt`:  Alternative names of the protected area, in a local language (see `langloc` value), when available. When multiple alternative names are present, names are separated by a semi-colon and space. String value.
	- _Example: "Lurë–Mali i Dejës"_

- `langloc`: The [three-character ISO language code](https://www.loc.gov/standards/iso639-2/php/code_list.php) of an official language of the country. This language code represents the language of the names in the `nameloc` and `namelocalt` properties.
	- _Example: "deu"_

- `type`: Designation of the protected area, typically in English. If this protected area was recognized or designated multiple times, multiple values can be present and separated by a semi-colon and space. String value.
	- _Example: "Wildlife Reserve"_

- `typeloc`:  Designation of the protected area, in a local language (see `langloc` value), when available. If this protected area was recognized or designated multiple times, multiple values can be present and separated by a semi-colon and space. String value.
	- _Example: "Rezervati Natyror i Menaxhaur"_

- `iso3`: The [three-character ISO country code](https://en.wikipedia.org/wiki/List_of_ISO_3166_country_codes) of the country that manages this protected area. String value.
	- _Example: "CAN"_

- `area`: TBD.

- `daterec`: The [edtf date](https://www.loc.gov/standards/datetime/) when this protected area was recognized or designated. If this protected area was recognized or designated multiple times, multiple dates can be present and separated by a semi-colon and space. String value.
	- _Example: "2004-01-01" or "2000-03; 2008-05-15"_

- `datelast`: The [edtf date](https://www.loc.gov/standards/datetime/) when this feature was last edited in the dataset. String value.
	- _Example: "2022-08-01"_

- `srcgeom`: The source of the geometry for this feature. Self-referential when the geometry was hand-curated. Additional source information can be found in this repo's sources folder. String value.
	- _Example: "pad-afghanistan"_

- `note`: An open-ended note about this feature. String value.
	- _Example: "Unable to confirm local designation, date is approximate."_

