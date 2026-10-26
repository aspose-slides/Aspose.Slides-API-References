---
title: IPortionFormat
second_title: Aspose.Slides für C++ API-Referenz
description: Diese Klasse enthält die Textabschnitt-Formatierungseigenschaften. Im Gegensatz zu IPortionFormatEffectiveData sind alle Eigenschaften dieser Klasse schreibbar.
type: docs
weight: 3329
url: /de/aspose.slides/iportionformat/
---
## IPortionFormat Klasse


This class contains the text portion formatting properties. Unlike [IPortionFormatEffectiveData](../iportionformateffectivedata/), all properties of this class are writeable.

```cpp
class IPortionFormat : public virtual Aspose::Slides::IBasePortionFormat,
                       public Aspose::Slides::IHyperlinkContainer
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Objekte vom Referenztyp im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Objekte vom Werttyp im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../ibaseportionformat/get_alternativelanguageid/)() | Gibt die Id einer alternativen Sprache zurück. Siehe [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() | Gibt den Lesezeichen-Bezeichner zurück. Siehe [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../ibaseportionformat/get_complexscriptfont/)() | Gibt die Schriftinformationen für komplexe Skripte zurück. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden sollte. Siehe [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../ibaseportionformat/get_eastasianfont/)() | Gibt die Ostasien-Schriftinformationen zurück. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden sollte. Siehe [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ibaseportionformat/get_effectformat/)() | Gibt die Text [EffectFormat](../effectformat/)-Eigenschaften zurück. Keine Vererbung angewendet. Nur lesbar [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](../ibaseportionformat/get_escapement/)() | Gibt den hoch- oder tiefgestellten Text zurück. Wert von -100 % (tiefgestellt) bis 100 % (hochgestellt). **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden sollte. Lesen **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ibaseportionformat/get_fillformat/)() | Gibt die Text [FillFormat](../fillformat/)-Eigenschaften zurück. Keine Vererbung angewendet. Nur lesbar [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](../ibaseportionformat/get_fontbold/)() | Bestimmt, ob die Schrift fett ist. Keine Vererbung angewendet. Siehe [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](../ibaseportionformat/get_fontheight/)() | Gibt die Schriftgröße eines Abschnitts zurück. **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass die Höhe undefiniert ist und vom Master geerbt werden sollte. Lesen **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](../ibaseportionformat/get_fontitalic/)() | Bestimmt, ob die Schrift kursiv ist. Keine Vererbung angewendet. Siehe [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../ibaseportionformat/get_fontunderline/)() | Gibt den Textunterstreichungstyp zurück. Keine Vererbung angewendet. Siehe [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../ibaseportionformat/get_highlightcolor/)() | Gibt die Farbe zurück, die zum Hervorheben von Text verwendet wird. Keine Vererbung angewendet. Nur lesbar [IColorFormat](../icolorformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Gibt den für Mausklick definierten Hyperlink zurück. Siehe [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Hyperlink-Manager Nur lesbar [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Gibt den für Maus-over definierten Hyperlink zurück. Siehe [IHyperlink](../ihyperlink/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../ibaseportionformat/get_ishardunderlinefill/)() | Bestimmt, ob der Unterstreichungsstil eigene [FillFormat](../fillformat/)-Eigenschaften besitzt oder sie von den [FillFormat](../fillformat/)-Eigenschaften des Textes erbt. Siehe [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../ibaseportionformat/get_ishardunderlineline/)() | Bestimmt, ob der Unterstreichungsstil eigene [LineFormat](../lineformat/)-Eigenschaften besitzt oder sie von den [LineFormat](../lineformat/)-Eigenschaften des Textes erbt. Siehe [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](../ibaseportionformat/get_kerningminimalsize/)() | Gibt die minimale Schriftgröße zurück, ab der Kerning aktiviert werden soll. **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden sollte. Lesen **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](../ibaseportionformat/get_kumimoji/)() | Bestimmt, ob die Zahlen das textspezifische östliche Sprach-vertikale Layout ignorieren sollen. Keine Vererbung angewendet. Siehe [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](../ibaseportionformat/get_languageid/)() | Gibt die Id einer Rechtschreibsprache zurück. Wird zum Prüfen von Rechtschreibung und Grammatik verwendet. Siehe [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../ibaseportionformat/get_latinfont/)() | Gibt die lateinische Schriftinformation zurück. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden sollte. Siehe [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ibaseportionformat/get_lineformat/)() | Gibt die [LineFormat](../lineformat/)-Eigenschaften für Textkontur zurück. Keine Vererbung angewendet. Nur lesbar [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](../ibaseportionformat/get_normaliseheight/)() | Bestimmt, ob die Höhe eines Textes normalisiert werden soll. Keine Vererbung angewendet. Siehe [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](../ibaseportionformat/get_proofdisabled/)() | Bestimmt, ob der Text nicht geprüft werden soll. Keine Vererbung angewendet. Siehe [NullableBool](../nullablebool/). |
| virtual **bool** [get_SmartTagClean](./get_smarttagclean/)() | Bestimmt, ob das Smart-Tag bereinigt werden soll. Keine Vererbung angewendet. Lesen **bool**. |
| virtual **float** [get_Spacing](../ibaseportionformat/get_spacing/)() | Gibt die Interzeichenabstandssteigerung zurück. **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden sollte. Lesen **float**. |
| virtual **bool** [get_SpellCheck](../ibaseportionformat/get_spellcheck/)() | Erhält einen Wert, der angibt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. Wenn diese Eigenschaft auf false gesetzt ist, werden Rechtschreibprüfungen für Textelemente unterdrückt. Wenn sie auf true gesetzt ist, ist die Rechtschreibprüfung erlaubt. Standardwert ist **false**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../ibaseportionformat/get_strikethroughtype/)() | Gibt den Durchstreichtyp eines Textes zurück. Keine Vererbung angewendet. Siehe [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../ibaseportionformat/get_symbolfont/)() | Gibt die symbolische Schriftinformation zurück. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden sollte. Siehe [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../ibaseportionformat/get_textcaptype/)() | Gibt den Typ der Textkapitalisierung zurück. Keine Vererbung angewendet. Siehe [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../ibaseportionformat/get_underlinefillformat/)() | Gibt die Unterstreichungs-Linien-[FillFormat](../fillformat/)-Eigenschaften zurück. Keine Vererbung angewendet. Nur lesbar [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../ibaseportionformat/get_underlinelineformat/)() | Gibt die [LineFormat](../lineformat/)-Eigenschaften zurück, die zum Umranden der Unterstreichungs-Linie verwendet werden. Keine Vererbung angewendet. Nur lesbar [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Erhält die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() | Erhält die effektiven Abschnittsformatierungsdaten mit angewandter Vererbung. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Erhält den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const&) Kopierkonstruktor. Kopiert tatsächlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) Zuweisungsoperator. Kopiert tatsächlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die gemeinsame Referenzzählung um den angegebenen Wert. |
| virtual void [set_AlternativeLanguageId](../ibaseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) | Setzt die Id einer alternativen Sprache. Schreiben [System::String](../../system/string/). |
| virtual void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) | Setzt den Lesezeichen-Bezeichner. Schreiben [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](../ibaseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Setzt die Schriftinformationen für komplexe Skripte. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden sollte. Schreiben [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](../ibaseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Setzt die Ostasien-Schriftinformationen. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden sollte. Schreiben [IFontData](../ifontdata/). |
| virtual void [set_Escapement](../ibaseportionformat/set_escapement/)(**float**) | Setzt den hoch- oder tiefgestellten Text. Wert von -100 % (tiefgestellt) bis 100 % (hochgestellt). **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden sollte. Schreiben **float**. |
| virtual void [set_FontBold](../ibaseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) | Bestimmt, ob die Schrift fett ist. Keine Vererbung angewendet. Schreiben [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](../ibaseportionformat/set_fontheight/)(**float**) | Setzt die Schriftgröße eines Abschnitts. **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass die Höhe undefiniert ist und vom Master geerbt werden sollte. Schreiben **float**. |
| virtual void [set_FontItalic](../ibaseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) | Bestimmt, ob die Schrift kursiv ist. Keine Vererbung angewendet. Schreiben [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](../ibaseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | Setzt den Textunterstreichungstyp. Keine Vererbung angewendet. Schreiben [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Setzt den für Mausklick definierten Hyperlink. Schreiben [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Setzt den für Maus-over definierten Hyperlink. Schreiben [IHyperlink](../ihyperlink/). |
| virtual void [set_IsHardUnderlineFill](../ibaseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | Bestimmt, ob der Unterstreichungsstil eigene [FillFormat](../fillformat/)-Eigenschaften besitzt oder sie von den [FillFormat](../fillformat/)-Eigenschaften des Textes erbt. Schreiben [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](../ibaseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) | Bestimmt, ob der Unterstreichungsstil eigene [LineFormat](../lineformat/)-Eigenschaften besitzt oder sie von den [LineFormat](../lineformat/)-Eigenschaften des Textes erbt. Schreiben [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](../ibaseportionformat/set_kerningminimalsize/)(**float**) | Setzt die minimale Schriftgröße, ab der Kerning aktiviert werden soll. **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden sollte. Schreiben **float**. |
| virtual void [set_Kumimoji](../ibaseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) | Bestimmt, ob die Zahlen das textspezifische östliche Sprach-vertikale Layout ignorieren sollen. Keine Vererbung angewendet. Schreiben [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](../ibaseportionformat/set_languageid/)([System::String](../../system/string/)) | Setzt die Id einer Rechtschreibsprache. Wird zum Prüfen von Rechtschreibung und Grammatik verwendet. Schreiben [System::String](../../system/string/). |
| virtual void [set_LatinFont](../ibaseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Setzt die lateinische Schriftinformation. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden sollte. Schreiben [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](../ibaseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) | Bestimmt, ob die Höhe eines Textes normalisiert werden soll. Keine Vererbung angewendet. Schreiben [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](../ibaseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) | Bestimmt, ob der Text nicht geprüft werden soll. Keine Vererbung angewendet. Schreiben [NullableBool](../nullablebool/). |
| virtual void [set_SmartTagClean](./set_smarttagclean/)(**bool**) | Bestimmt, ob das Smart-Tag bereinigt werden soll. Keine Vererbung angewendet. Schreiben **bool**. |
| virtual void [set_Spacing](../ibaseportionformat/set_spacing/)(**float**) | Setzt die Interzeichenabstandssteigerung. **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden sollte. Schreiben **float**. |
| virtual void [set_SpellCheck](../ibaseportionformat/set_spellcheck/)(**bool**) | Setzt einen Wert, der angibt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. Wenn diese Eigenschaft auf false gesetzt wird, werden Rechtschreibprüfungen für Textelemente unterdrückt. Wenn sie auf true gesetzt wird, ist die Rechtschreibprüfung erlaubt. Standardwert ist **false**. |
| virtual void [set_StrikethroughType](../ibaseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | Setzt den Durchstreichtyp eines Textes. Keine Vererbung angewendet. Schreiben [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](../ibaseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Setzt die symbolische Schriftinformation. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden sollte. Schreiben [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](../ibaseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | Setzt den Typ der Textkapitalisierung. Keine Vererbung angewendet. Schreiben [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem weak-Zeiger (statt shared). Ermöglicht das Umschalten von Zeigern in Containern in den weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Erhält den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht die gemeinsame Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen smart-Pointern oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt die gemeinsame Referenzzählung zurück. Sollte nicht direkt aufgerufen werden; stattdessen smart-Pointern oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte zu einem String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht die weak-Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen smart-Pointern oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert die weak-Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen smart-Pointern oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Anmerkungen


Diese Klasse wird verwendet, um die für den jeweiligen Abschnitt definierten Textabschnitt-Formatierungseigenschaften zurückzugeben und zu manipulieren. Das bedeutet, dass beim Abrufen von Werten keine Vererbung angewendet wird, sodass Sie in den meisten Fällen Werte erhalten, die „undefiniert“ bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich vererbter Werte zu erhalten, müssen Sie die [IPortionFormat::GetEffective](./geteffective/)-Methode verwenden, die eine [IPortionFormatEffectiveData](../iportionformateffectivedata/)-Instanz zurückgibt.

## Siehe auch

* Klasse [IBasePortionFormat](../ibaseportionformat/)
* Klasse [IHyperlinkContainer](../ihyperlinkcontainer/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)