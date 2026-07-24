---
title: BasePortionFormat
second_title: Aspose.Slides für C++ API Referenz
description: Gemeinsame Formatierungseigenschaften für Textabschnitte.
type: docs
weight: 144
url: /de/aspose.slides/baseportionformat/
---
## BasePortionFormat Klasse

Gemeinsame Formatierungseigenschaften für Textabschnitte.

```cpp
class BasePortionFormat : public Aspose::Slides::PVIObject,
                          public virtual Aspose::Slides::IBasePortionFormat
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Vergleicht mit dem angegebenen Objekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() override | Gibt die ID einer alternativen Sprache zurück. Lesen [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() override | Gibt die Schriftartinformationen für komplexe Skripte zurück. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden soll. Lesen [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() override | Gibt die ostasiatischen Schriftartinformationen zurück. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden soll. Lesen [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() override | Gibt die Text-[EffectFormat](../effectformat/)-Eigenschaften zurück. Keine Vererbung angewendet. Nur lesbar [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](./get_escapement/)() override | Gibt den Hoch- oder Tiefgestellt-Text zurück. Wertebereich von -100 % (Tiefstellung) bis 100 % (Hochstellung). **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden soll. Lesen **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | Gibt die Text-[FillFormat](../fillformat/)-Eigenschaften zurück. Keine Vererbung angewendet. Nur lesbar [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() override | Bestimmt, ob die Schriftart fett ist. Keine Vererbung angewendet. Lesen [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](./get_fontheight/)() override | Gibt die Schrifthöh eines Abschnitts zurück. **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass die Höhe undefiniert ist und vom Master geerbt werden soll. Lesen **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() override | Bestimmt, ob die Schriftart kursiv ist. Keine Vererbung angewendet. Lesen [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() override | Gibt den Textunterstreichungstyp zurück. Keine Vererbung angewendet. Lesen [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() override | Gibt die Farbe zurück, die zum Hervorheben von Text verwendet wird. Keine Vererbung angewendet. Nur lesbar [IColorFormat](../icolorformat/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() override | Bestimmt, ob der Unterstreichungsstil eigene [FillFormat](../fillformat/)-Eigenschaften hat oder sie von den [FillFormat](../fillformat/)-Eigenschaften des Textes erbt. Lesen [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() override | Bestimmt, ob der Unterstreichungsstil eigene [LineFormat](../lineformat/)-Eigenschaften hat oder sie von den [LineFormat](../lineformat/)-Eigenschaften des Textes erbt. Lesen [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() override | Gibt die minimale Schriftgröße zurück, ab der Kerning aktiviert werden soll. **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden soll. Lesen **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() override | Bestimmt, ob die Zahlen das spezifische vertikale Textlayout östlicher Sprachen ignorieren sollen. Keine Vererbung angewendet. Lesen [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() override | Gibt die ID einer Korrektursprache zurück. Wird zur Rechtschreib- und Grammatikprüfung verwendet. Lesen [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() override | Gibt die lateinische Schriftartinformation zurück. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden soll. Lesen [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | Gibt die [LineFormat](../lineformat/)-Eigenschaften für die Textumrandung zurück. Keine Vererbung angewendet. Nur lesbar [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() override | Bestimmt, ob die Höhe eines Textes normalisiert werden soll. Keine Vererbung angewendet. Lesen [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Gibt das Parent_Immediate-Objekt zurück. Nur lesbar [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Gibt das übergeordnete [IPresentationComponent](../ipresentationcomponent/) zurück. Nur lesbar [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() override | Bestimmt, ob der Text nicht geprüft werden soll. Keine Vererbung angewendet. Lesen [NullableBool](../nullablebool/). |
| **float** [get_Spacing](./get_spacing/)() override | Gibt die Erhöhung des Zeichenabstands zurück. **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden soll. Lesen **float**. |
| **bool** [get_SpellCheck](./get_spellcheck/)() override | Ermittelt einen Wert, der angibt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. Wenn diese Eigenschaft auf false gesetzt ist, werden Rechtschreibprüfungen für Textelemente unterdrückt. Wenn sie auf true gesetzt ist, ist die Rechtschreibprüfung erlaubt. Standardwert ist **false**. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() override | Gibt den Durchstreichungstyp eines Textes zurück. Keine Vererbung angewendet. Lesen [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() override | Gibt die symbolischen Schriftartinformationen zurück. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden soll. Lesen [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() override | Gibt die Art der Textkapitalisierung zurück. Keine Vererbung angewendet. Lesen [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() override | Gibt die Unterstreichungslinien-[FillFormat](../fillformat/)-Eigenschaften zurück. Keine Vererbung angewendet. Nur lesbar [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() override | Gibt die [LineFormat](../lineformat/)-Eigenschaften zurück, die zur Konturierung der Unterstreichungslinie verwendet werden. Keine Vererbung angewendet. Nur lesbar [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Gibt den Hash-Code zurück. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-'is'-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
| [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsam genutzten Referenzzähler um den angegebenen Wert. |
| void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) override | Setzt die ID einer alternativen Sprache. Schreiben [System::String](../../system/string/). |
| void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Setzt die Schriftartinformationen für komplexe Skripte. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden soll. Schreiben [IFontData](../ifontdata/). |
| void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Setzt die ostasiatischen Schriftartinformationen. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden soll. Schreiben [IFontData](../ifontdata/). |
| void [set_Escapement](./set_escapement/)(**float**) override | Setzt den Hoch- oder Tiefgestellt-Text. Wertebereich von -100 % (Tiefstellung) bis 100 % (Hochstellung). **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden soll. Schreiben **float**. |
| void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) override | Bestimmt, ob die Schriftart fett ist. Keine Vererbung angewendet. Schreiben [NullableBool](../nullablebool/). |
| void [set_FontHeight](./set_fontheight/)(**float**) override | Setzt die Schrifthöhe eines Abschnitts. **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass die Höhe undefiniert ist und vom Master geerbt werden soll. Schreiben **float**. |
| void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) override | Bestimmt, ob die Schriftart kursiv ist. Keine Vererbung angewendet. Schreiben [NullableBool](../nullablebool/). |
| void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | Setzt den Textunterstreichungstyp. Keine Vererbung angewendet. Schreiben [TextUnderlineType](../textunderlinetype/). |
| void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | Bestimmt, ob der Unterstreichungsstil eigene [FillFormat](../fillformat/)-Eigenschaften hat oder sie von den [FillFormat](../fillformat/)-Eigenschaften des Textes erbt. Schreiben [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | Bestimmt, ob der Unterstreichungsstil eigene [LineFormat](../lineformat/)-Eigenschaften hat oder sie von den [LineFormat](../lineformat/)-Eigenschaften des Textes erbt. Schreiben [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) override | Setzt die minimale Schriftgröße, ab der Kerning aktiviert werden soll. **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden soll. Schreiben **float**. |
| void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) override | Bestimmt, ob die Zahlen das spezifische vertikale Textlayout östlicher Sprachen ignorieren sollen. Keine Vererbung angewendet. Schreiben [NullableBool](../nullablebool/). |
| void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) override | Setzt die ID einer Korrektursprache. Wird zur Rechtschreib- und Grammatikprüfung verwendet. Schreiben [System::String](../../system/string/). |
| void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Setzt die lateinischen Schriftartinformationen. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden soll. Schreiben [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) override | Bestimmt, ob die Höhe eines Textes normalisiert werden soll. Keine Vererbung angewendet. Schreiben [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) override | Bestimmt, ob der Text nicht geprüft werden soll. Keine Vererbung angewendet. Schreiben [NullableBool](../nullablebool/). |
| void [set_Spacing](./set_spacing/)(**float**) override | Setzt die Erhöhung des Zeichenabstands. **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden soll. Schreiben **float**. |
| void [set_SpellCheck](./set_spellcheck/)(**bool**) override | Setzt einen Wert, der angibt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. Wenn diese Eigenschaft auf false gesetzt ist, werden Rechtschreibprüfungen für Textelemente unterdrückt. Wenn sie auf true gesetzt ist, ist die Rechtschreibprüfung erlaubt. Standardwert ist **false**. |
| void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | Setzt den Durchstreichungstyp eines Textes. Keine Vererbung angewendet. Schreiben [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Setzt die symbolischen Schriftartinformationen. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden soll. Schreiben [IFontData](../ifontdata/). |
| void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | Setzt die Art der Textkapitalisierung. Keine Vererbung angewendet. Schreiben [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Erlaubt das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsam genutzten Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsam genutzten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsam genutzten Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe Auch

* Klasse [PVIObject](../pviobject/)
* Klasse [IBasePortionFormat](../ibaseportionformat/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)