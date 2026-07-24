---
title: IBasePortionFormat
second_title: Aspose.Slides für C++ API-Referenz
description: Diese Klasse enthält die Formatierungseigenschaften des Textabschnitts. Im Gegensatz zu IPortionFormatEffectiveData sind alle Eigenschaften dieser Klasse schreibbar.
type: docs
weight: 1457
url: /de/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat Klasse


Diese Klasse enthält die Formatierungseigenschaften des Textabschnitts. Im Gegensatz zu [IPortionFormatEffectiveData](../iportionformateffectivedata/) sind alle Eigenschaften dieser Klasse schreibbar.

```cpp
class IBasePortionFormat : public virtual System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte anhand der C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Objekte von Referenztyp im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Objekte vom Werttyp im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN keiner beliebigen Zahl, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN keiner beliebigen Zahl, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für den internen Gebrauch. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | Gibt die Id einer alternativen Sprache zurück. Siehe [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | Gibt die Schriftartinformationen für komplexe Skripte zurück. Null bedeutet, dass die Schriftart nicht definiert ist und vom Master geerbt werden sollte. Siehe [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | Gibt die Ostasiatischen Schriftartinformationen zurück. Null bedeutet, dass die Schriftart nicht definiert ist und vom Master geerbt werden sollte. Siehe [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() | Gibt die Text [EffectFormat](../effectformat/)-Eigenschaften zurück. Keine Vererbung angewendet. Nur lesen [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](./get_escapement/)() | Gibt den hoch- oder tiefgestellten Text zurück. Wertbereich von -100 % (Tiefstellung) bis 100 % (Hochstellung). **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass der Wert nicht definiert ist und vom Master geerbt werden sollte. Nur lesen **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() | Gibt die Text [FillFormat](../fillformat/)-Eigenschaften zurück. Keine Vererbung angewendet. Nur lesen [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() | Bestimmt, ob die Schriftart fett ist. Keine Vererbung angewendet. Siehe [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](./get_fontheight/)() | Gibt die Schriftgradhöhe eines Abschnitts zurück. **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass die Höhe nicht definiert ist und vom Master geerbt werden sollte. Nur lesen **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() | Bestimmt, ob die Schrift kursiv ist. Keine Vererbung angewendet. Siehe [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | Gibt den Unterstreichungstyp des Textes zurück. Keine Vererbung angewendet. Siehe [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() | Gibt die zum Hervorheben von Text verwendete Farbe zurück. Keine Vererbung angewendet. Nur lesen [IColorFormat](../icolorformat/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | Bestimmt, ob der Unterstreichungsstil eigene [FillFormat](../fillformat/)-Eigenschaften hat oder sie von den [FillFormat](../fillformat/)-Eigenschaften des Textes erbt. Siehe [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | Bestimmt, ob der Unterstreichungsstil eigene [LineFormat](../lineformat/)-Eigenschaften hat oder sie von den [LineFormat](../lineformat/)-Eigenschaften des Textes erbt. Siehe [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | Gibt die minimale Schriftgröße zurück, für die Kerning aktiviert werden soll. **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass der Wert nicht definiert ist und vom Master geerbt werden sollte. Nur lesen **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() | Bestimmt, ob Zahlen das östlich-sprachspezifische vertikale Textlayout ignorieren sollen. Keine Vererbung angewendet. Siehe [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | Gibt die Id einer Korrektursprache zurück. Wird zur Rechtschreib- und Grammatikprüfung verwendet. Siehe [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | Gibt die lateinische Schriftartinformation zurück. Null bedeutet, dass die Schriftart nicht definiert ist und vom Master geerbt werden sollte. Siehe [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() | Gibt die [LineFormat](../lineformat/)-Eigenschaften für Textumrandung zurück. Keine Vererbung angewendet. Nur lesen [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() | Bestimmt, ob die Höhe eines Textes normalisiert werden soll. Keine Vererbung angewendet. Siehe [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() | Bestimmt, ob der Text nicht korrigiert werden soll. Keine Vererbung angewendet. Siehe [NullableBool](../nullablebool/). |
| virtual **float** [get_Spacing](./get_spacing/)() | Gibt die Erhöhung des Zeichenzwischenabstands zurück. **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass der Wert nicht definiert ist und vom Master geerbt werden sollte. Nur lesen **float**. |
| virtual **bool** [get_SpellCheck](./get_spellcheck/)() | Ermittelt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. Wenn diese Eigenschaft auf false gesetzt ist, werden Rechtschreibprüfungen für Textelemente unterdrückt. Wenn sie auf true gesetzt ist, ist die Rechtschreibprüfung zulässig. Standardwert ist **false**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | Gibt den Durchstreichungstyp eines Textes zurück. Keine Vererbung angewendet. Siehe [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | Gibt die symbolische Schriftartinformation zurück. Null bedeutet, dass die Schriftart nicht definiert ist und vom Master geerbt werden sollte. Siehe [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | Gibt den Typ der Textkapitalisierung zurück. Keine Vererbung angewendet. Siehe [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | Gibt die Unterstreichungszeile [FillFormat](../fillformat/)-Eigenschaften zurück. Keine Vererbung angewendet. Nur lesen [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | Gibt die [LineFormat](../lineformat/)-Eigenschaften zurück, die zur Umrandung der Unterstreichungszeile verwendet werden. Keine Vererbung angewendet. Nur lesen [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Erhält die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Erhält den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt das Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert tatsächlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert tatsächlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttypobjekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den geteilten Referenzzähler um den angegebenen Wert. |
| virtual void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) | Setzt die Id einer alternativen Sprache. Schreiben [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Setzt die Schriftartinformationen für komplexe Skripte. Null bedeutet, dass die Schriftart nicht definiert ist und vom Master geerbt werden sollte. Schreiben [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Setzt die Ostasiatischen Schriftartinformationen. Null bedeutet, dass die Schriftart nicht definiert ist und vom Master geerbt werden sollte. Schreiben [IFontData](../ifontdata/). |
| virtual void [set_Escapement](./set_escapement/)(**float**) | Setzt den hoch- oder tiefgestellten Text. Wertbereich von -100 % (Tiefstellung) bis 100 % (Hochstellung). **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass der Wert nicht definiert ist und vom Master geerbt werden sollte. Schreiben **float**. |
| virtual void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) | Bestimmt, ob die Schriftart fett ist. Keine Vererbung angewendet. Schreiben [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](./set_fontheight/)(**float**) | Setzt die Schriftgradhöhe eines Abschnitts. **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass die Höhe nicht definiert ist und vom Master geerbt werden sollte. Schreiben **float**. |
| virtual void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) | Bestimmt, ob die Schrift kursiv ist. Keine Vererbung angewendet. Schreiben [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | Setzt den Unterstreichungstyp des Textes. Keine Vererbung angewendet. Schreiben [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | Bestimmt, ob der Unterstreichungsstil eigene [FillFormat](../fillformat/)-Eigenschaften hat oder sie von den [FillFormat](../fillformat/)-Eigenschaften des Textes erbt. Schreiben [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) | Bestimmt, ob der Unterstreichungsstil eigene [LineFormat](../lineformat/)-Eigenschaften hat oder sie von den [LineFormat](../lineformat/)-Eigenschaften des Textes erbt. Schreiben [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) | Setzt die minimale Schriftgröße, für die Kerning aktiviert werden soll. **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass der Wert nicht definiert ist und vom Master geerbt werden sollte. Schreiben **float**. |
| virtual void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) | Bestimmt, ob Zahlen das östlich-sprachspezifische vertikale Textlayout ignorieren sollen. Keine Vererbung angewendet. Schreiben [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) | Setzt die Id einer Korrektursprache. Wird zur Rechtschreib- und Grammatikprüfung verwendet. Schreiben [System::String](../../system/string/). |
| virtual void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Setzt die lateinische Schriftartinformation. Null bedeutet, dass die Schriftart nicht definiert ist und vom Master geerbt werden sollte. Schreiben [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) | Bestimmt, ob die Höhe eines Textes normalisiert werden soll. Keine Vererbung angewendet. Schreiben [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) | Bestimmt, ob der Text nicht korrigiert werden soll. Keine Vererbung angewendet. Schreiben [NullableBool](../nullablebool/). |
| virtual void [set_Spacing](./set_spacing/)(**float**) | Setzt die Erhöhung des Zeichenzwischenabstands. **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass der Wert nicht definiert ist und vom Master geerbt werden sollte. Schreiben **float**. |
| virtual void [set_SpellCheck](./set_spellcheck/)(**bool**) | Setzt einen Wert, der angibt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. Wenn diese Eigenschaft auf false gesetzt ist, werden Rechtschreibprüfungen für Textelemente unterdrückt. Wenn sie auf true gesetzt ist, ist die Rechtschreibprüfung zulässig. Standardwert ist **false**. |
| virtual void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | Setzt den Durchstreichungstyp eines Textes. Keine Vererbung angewendet. Schreiben [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Setzt die symbolische Schriftartinformation. Null bedeutet, dass die Schriftart nicht definiert ist und vom Master geerbt werden sollte. Schreiben [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | Setzt den Typ der Textkapitalisierung. Keine Vererbung angewendet. Schreiben [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem Weak-Pointer (statt Shared). Ermöglicht das Umschalten von Zeigern in Containern auf den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Erhält den aktuellen Wert des geteilten Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den geteilten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den geteilten Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Anmerkungen


Diese Klasse wird verwendet, um die für den jeweiligen Abschnitt definierten Formatierungseigenschaften des Textabschnitts zurückzugeben und zu manipulieren. Das bedeutet, dass beim Abrufen von Werten keine Vererbung angewendet wird, sodass in den meisten Fällen Werte zurückgegeben werden, die „undefiniert“ bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich geerbter Werte zu erhalten, müssen Sie die Methode [IPortionFormat::GetEffective](../iportionformat/geteffective/) verwenden, die eine [IPortionFormatEffectiveData](../iportionformateffectivedata/)-Instanz zurückgibt.

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)