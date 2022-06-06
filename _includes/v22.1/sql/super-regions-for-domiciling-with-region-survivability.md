If you want to do data domiciling for databases with [region survival goals](multiregion-overview.html#survive-region-failures) {% if page.name == "multiregion-overview.md" %} using the higher-level multiregion abstractions, you must use Super Regions {% else %} using the higher-level [multiregion abstractions](multiregion-overview.html), you must use [Super Regions](multiregion-overview.html#super-regions) {% endif %}. Using [`ALTER DATABASE ... PLACEMENT RESTRICTED`](placement-restricted.html) will not work for databases that are set up with region survival goals.