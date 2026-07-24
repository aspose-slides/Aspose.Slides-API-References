---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides für C++ API-Referenz
description: Basisschnittstelle für unveränderliche Objekte, die effektive Textabschnitt-Formatierungseigenschaften enthalten.
type: docs
weight: 1470
url: /de/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData Klasse

Base interface for immutable objects which contain effective text portion formatting properties.

```cpp
class IBasePortionFormatEffectiveData : public virtual System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mit C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert C#-stiligen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert gleich ist, einschließlich NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert C#-stiligen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert gleich ist, einschließlich NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | Gibt die Id einer alternativen Sprache zurück. Nur-Lese [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | Gibt die Informationen zur komplexen Skript-Schriftart zurück. Nur-Lese [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | Gibt die Informationen zur ostasiatischen Schriftart zurück. Nur-Lese [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [get_EffectFormat](./get_effectformat/)() | Gibt die Text [EffectFormat](../effectformat/) Eigenschaften zurück. Nur-Lese [IEffectFormatEffectiveData](../ieffectformateffectivedata/). |
| virtual **float** [get_Escapement](./get_escapement/)() | Gibt den hoch- oder tiefgestellten Text zurück. Wert von -100% (tiefgestellt) bis 100% (hochgestellt). Nur-Lese **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_FillFormat](./get_fillformat/)() | Gibt die Text [FillFormat](../fillformat/) Eigenschaften zurück. Nur-Lese [IFillFormatEffectiveData](../ifillformateffectivedata/). |
| virtual **bool** [get_FontBold](./get_fontbold/)() | Bestimmt, ob die Schrift fett ist. Nur-Lese **bool**. |
| virtual **float** [get_FontHeight](./get_fontheight/)() | Gibt die Schriftgröße des Textabschnitts in Punkten zurück. Nur-Lese **float**. |
| virtual **bool** [get_FontItalic](./get_fontitalic/)() | Bestimmt, ob die Schrift kursiv ist. Nur-Lese **bool**. |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | Gibt den Textunterstreichungs-Typ zurück. Nur-Lese [TextUnderlineType](../textunderlinetype/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_HighlightColor](./get_highlightcolor/)() | Gibt die zum Hervorheben von Text verwendete Farbe zurück. Nur-Lese [System::Drawing::Color](../../system.drawing/color/). |
| virtual **bool** [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | Bestimmt, ob der Unterstreichungsstil eigene [FillFormat](../fillformat/) Eigenschaften hat oder sie von den [FillFormat](../fillformat/) Eigenschaften des Textes erbt. Nur-Lese **bool**. |
| virtual **bool** [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | Bestimmt, ob der Unterstreichungsstil eigene [LineFormat](../lineformat/) Eigenschaften hat oder sie von den [LineFormat](../lineformat/) Eigenschaften des Textes erbt. Nur-Lese **bool**. |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | Gibt die minimale Schriftgröße zurück, für die Kerning aktiviert werden soll. Nur-Lese **float**. |
| virtual **bool** [get_Kumimoji](./get_kumimoji/)() | Bestimmt, ob die Zahlen das spezifische vertikale Layout von östlichen Sprachen im Text ignorieren sollten. Nur-Lese **bool**. |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | Gibt die Id einer Sprache zurück. Nur-Lese [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | Gibt die Informationen zur lateinischen Schriftart zurück. Nur-Lese [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_LineFormat](./get_lineformat/)() | Gibt die [LineFormat](../lineformat/) Eigenschaften für Textumrandung zurück. Nur-Lese [ILineFormatEffectiveData](../ilineformateffectivedata/). |
| virtual **bool** [get_NormaliseHeight](./get_normaliseheight/)() | Bestimmt, ob die Höhe eines Textes normalisiert werden soll. Nur-Lese **bool**. |
| virtual **bool** [get_ProofDisabled](./get_proofdisabled/)() | Bestimmt, ob der Text nicht geprüft werden soll. Nur-Lese **bool**. |
| virtual **bool** [get_SmartTagClean](./get_smarttagclean/)() | Bestimmt, ob das Smart-Tag bereinigt werden soll. Nur-Lese **bool**. |
| virtual **float** [get_Spacing](./get_spacing/)() | Gibt die Erhöhung des Zeichenabstands in Punkten zurück. Nur-Lese **float**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | Gibt den Durchstreichungs-Typ eines Textes zurück. Nur-Lese [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | Gibt die symbolische Schriftart-Information zurück. Nur-Lese [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | Gibt die Art der Textschreibung zurück. Nur-Lese [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | Gibt die Unterstreichungs-Linien [FillFormat](../fillformat/) Eigenschaften zurück. Nur-Lese [IFillFormatEffectiveData](../ifillformateffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | Gibt die [LineFormat](../lineformat/) Eigenschaften zurück, die zur Umrandung der Unterstreichungs-Linie verwendet werden. Nur-Lese [ILineFormatEffectiveData](../ilineformateffectivedata/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Erhält die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Erhält den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/) Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C# 'is' Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das C# lock()-Statement zum Sperren. Direkt aufrufen oder das [LockContext](../../system/lockcontext/) Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert tatsächlich nichts, initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert tatsächlich nichts, initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz einen Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die gemeinsame Referenzzähler um den angegebenen Wert. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt einem geteilten). Erlaubt das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Erhält den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/)) Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das C# lock()-Statement zum Entsperren. Direkt aufrufen oder das [LockContext](../../system/lockcontext/) Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |
## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)