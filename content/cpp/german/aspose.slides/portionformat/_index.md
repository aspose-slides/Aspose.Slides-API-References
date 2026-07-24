---
title: PortionFormat
second_title: Aspose.Slides für C++ API-Referenz
description: Diese Klasse enthält die Textabschnitt-Formatierungseigenschaften. Im Gegensatz zu IPortionFormatEffectiveData sind alle Eigenschaften dieser Klasse schreibbar.
type: docs
weight: 4811
url: /de/aspose.slides/portionformat/
---
## PortionFormat Klasse


Diese Klasse enthält die Formatierungseigenschaften des Textabschnitts. Im Gegensatz zu [IPortionFormatEffectiveData](../iportionformateffectivedata/) sind alle Eigenschaften dieser Klasse schreibbar.

```cpp
class PortionFormat : public Aspose::Slides::BasePortionFormat,
                      public Aspose::Slides::IPortionFormat
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Vergleicht mit dem angegebenen Objekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte anhand der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl sie gemäß IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich sind. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl sie gemäß IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich sind. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](../baseportionformat/get_alternativelanguageid/)() override | Gibt die Id einer alternativen Sprache zurück. Lesen [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() override | Gibt die Lesezeichenkennung zurück. Lesen [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../baseportionformat/get_complexscriptfont/)() override | Gibt die Schriftinformationen für komplexe Skripte zurück. Null bedeutet, dass die Schriftart undefiniert ist und vom Master ererbt werden sollte. Lesen [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../baseportionformat/get_eastasianfont/)() override | Gibt die ostasiatischen Schriftinformationen zurück. Null bedeutet, dass die Schriftart undefiniert ist und vom Master ererbt werden sollte. Lesen [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../baseportionformat/get_effectformat/)() override | Gibt die Text-[EffectFormat](../effectformat/)-Eigenschaften zurück. Keine Vererbung angewendet. Nur lesend [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](../baseportionformat/get_escapement/)() override | Gibt den Ober- oder Tiefstellungstext zurück. Wert von -100 % (Tiefstellung) bis 100 % (Oberstellung). **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass der Wert undefiniert ist und vom Master ererbt werden sollte. Lesen **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../baseportionformat/get_fillformat/)() override | Gibt die Text-[FillFormat](../fillformat/)-Eigenschaften zurück. Keine Vererbung angewendet. Nur lesend [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](../baseportionformat/get_fontbold/)() override | Bestimmt, ob die Schriftart fett ist. Keine Vererbung angewendet. Lesen [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](../baseportionformat/get_fontheight/)() override | Gibt die Schrifthöhe eines Abschnitts zurück. **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass die Höhe undefiniert ist und vom Master ererbt werden sollte. Lesen **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](../baseportionformat/get_fontitalic/)() override | Bestimmt, ob die Schrift kursiv ist. Keine Vererbung angewendet. Lesen [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../baseportionformat/get_fontunderline/)() override | Gibt den Textunterstreichungstyp zurück. Keine Vererbung angewendet. Lesen [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../baseportionformat/get_highlightcolor/)() override | Gibt die zum Hervorheben eines Textes verwendete Farbe zurück. Keine Vererbung angewendet. Nur lesend [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() override | Gibt den für Mausklick definierten Hyperlink zurück. Lesen [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](./get_hyperlinkmanager/)() override | Hyperlink-Manager. Nur lesend [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() override | Gibt den für Maus-over definierten Hyperlink zurück. Lesen [IHyperlink](../ihyperlink/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../baseportionformat/get_ishardunderlinefill/)() override | Bestimmt, ob der Unterstreichungsstil eigene [FillFormat](../fillformat/)-Eigenschaften hat oder sie von den [FillFormat](../fillformat/)-Eigenschaften des Textes erbt. Lesen [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../baseportionformat/get_ishardunderlineline/)() override | Bestimmt, ob der Unterstreichungsstil eigene [LineFormat](../lineformat/)-Eigenschaften hat oder sie von den [LineFormat](../lineformat/)-Eigenschaften des Textes erbt. Lesen [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](../baseportionformat/get_kerningminimalsize/)() override | Gibt die minimale Schriftgröße zurück, ab der Kerning aktiviert werden soll. **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass der Wert undefiniert ist und vom Master ererbt werden sollte. Lesen **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](../baseportionformat/get_kumimoji/)() override | Bestimmt, ob die Zahlen die textspezifische vertikale Layout-Anordnung für ostasiatische Sprachen ignorieren sollen. Keine Vererbung angewendet. Lesen [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](../baseportionformat/get_languageid/)() override | Gibt die Id einer Korrektursprache zurück. Wird für Rechtschreib- und Grammatikprüfung verwendet. Lesen [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../baseportionformat/get_latinfont/)() override | Gibt die lateinischen Schriftinformationen zurück. Null bedeutet, dass die Schriftart undefiniert ist und vom Master ererbt werden sollte. Lesen [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../baseportionformat/get_lineformat/)() override | Gibt die [LineFormat](../lineformat/)-Eigenschaften für Textumrandung zurück. Keine Vererbung angewendet. Nur lesend [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](../baseportionformat/get_normaliseheight/)() override | Bestimmt, ob die Höhe eines Textes normalisiert werden soll. Keine Vererbung angewendet. Lesen [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Gibt das Parent_Immediate-Objekt zurück. Nur lesend [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Gibt den übergeordneten [IPresentationComponent](../ipresentationcomponent/) zurück. Nur lesend [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](../baseportionformat/get_proofdisabled/)() override | Bestimmt, ob der Text nicht geprüft werden soll. Keine Vererbung angewendet. Lesen [NullableBool](../nullablebool/). |
| **bool** [get_SmartTagClean](./get_smarttagclean/)() override | Bestimmt, ob das Smart-Tag bereinigt werden soll. Keine Vererbung angewendet. Lesen **bool**. |
| **float** [get_Spacing](../baseportionformat/get_spacing/)() override | Gibt die Interzeichenabstandserhöhung zurück. **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass der Wert undefiniert ist und vom Master ererbt werden sollte. Lesen **float**. |
| **bool** [get_SpellCheck](../baseportionformat/get_spellcheck/)() override | Ermittelt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. Wenn diese Eigenschaft auf false gesetzt ist, werden Rechtschreibprüfungen für Textelemente unterdrückt. Bei true ist die Rechtschreibprüfung erlaubt. Der Standardwert ist **false**. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../baseportionformat/get_strikethroughtype/)() override | Gibt den Durchstreichungstyp eines Textes zurück. Keine Vererbung angewendet. Lesen [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../baseportionformat/get_symbolfont/)() override | Gibt die symbolischen Schriftinformationen zurück. Null bedeutet, dass die Schriftart undefiniert ist und vom Master ererbt werden sollte. Lesen [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../baseportionformat/get_textcaptype/)() override | Gibt den Typ der Textgroßschreibung zurück. Keine Vererbung angewendet. Lesen [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../baseportionformat/get_underlinefillformat/)() override | Gibt die Unterstreichungs-[FillFormat](../fillformat/)-Eigenschaften zurück. Keine Vererbung angewendet. Nur lesend [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../baseportionformat/get_underlinelineformat/)() override | Gibt die [LineFormat](../lineformat/)-Eigenschaften zurück, die zum Umranden der Unterstreichungslinie verwendet werden. Keine Vererbung angewendet. Nur lesend [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Erhält die Referenzzähler-Datenstruktur, die mit dem Objekt verbunden ist. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() override | Erhält die effektiven Formatierungsdaten des Abschnitts mit angewandter Vererbung. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Gibt den Hash-Code zurück. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Erhält den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das Sentry-Objekt [LockContext](../../system/lockcontext/) verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
| [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert tatsächlich nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert tatsächlich nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [PortionFormat](./portionformat/)() | Initialisiert eine neue Instanz der Klasse [PortionFormat](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von String und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die gemeinsam genutzte Referenzzählung um den angegebenen Wert. |
| void [set_AlternativeLanguageId](../baseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) override | Setzt die Id einer alternativen Sprache. Schreiben [System::String](../../system/string/). |
| void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) override | Setzt die Lesezeichenkennung. Schreiben [System::String](../../system/string/). |
| void [set_ComplexScriptFont](../baseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Setzt die Schriftinformationen für komplexe Skripte. Null bedeutet, dass die Schriftart undefiniert ist und vom Master ererbt werden sollte. Schreiben [IFontData](../ifontdata/). |
| void [set_EastAsianFont](../baseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Setzt die ostasiatischen Schriftinformationen. Null bedeutet, dass die Schriftart undefiniert ist und vom Master ererbt werden sollte. Schreiben [IFontData](../ifontdata/). |
| void [set_Escapement](../baseportionformat/set_escapement/)(**float**) override | Setzt den Ober- oder Tiefstellungstext. Wert von -100 % (Tiefstellung) bis 100 % (Oberstellung). **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass der Wert undefiniert ist und vom Master ererbt werden sollte. Schreiben **float**. |
| void [set_FontBold](../baseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) override | Bestimmt, ob die Schriftart fett ist. Keine Vererbung angewendet. Schreiben [NullableBool](../nullablebool/). |
| void [set_FontHeight](../baseportionformat/set_fontheight/)(**float**) override | Setzt die Schrifthöhe eines Abschnitts. **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass die Höhe undefiniert ist und vom Master ererbt werden sollte. Schreiben **float**. |
| void [set_FontItalic](../baseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) override | Bestimmt, ob die Schrift kursiv ist. Keine Vererbung angewendet. Schreiben [NullableBool](../nullablebool/). |
| void [set_FontUnderline](../baseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | Setzt den Textunterstreichungstyp. Keine Vererbung angewendet. Schreiben [TextUnderlineType](../textunderlinetype/). |
| void [set_HyperlinkClick](./set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Setzt den für Mausklick definierten Hyperlink. Schreiben [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](./set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Setzt den für Maus-over definierten Hyperlink. Schreiben [IHyperlink](../ihyperlink/). |
| void [set_IsHardUnderlineFill](../baseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | Bestimmt, ob der Unterstreichungsstil eigene [FillFormat](../fillformat/)-Eigenschaften hat oder sie von den [FillFormat](../fillformat/)-Eigenschaften des Textes erbt. Schreiben [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](../baseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | Bestimmt, ob der Unterstreichungsstil eigene [LineFormat](../lineformat/)-Eigenschaften hat oder sie von den [LineFormat](../lineformat/)-Eigenschaften des Textes erbt. Schreiben [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](../baseportionformat/set_kerningminimalsize/)(**float**) override | Setzt die minimale Schriftgröße, ab der Kerning aktiviert werden soll. **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass der Wert undefiniert ist und vom Master ererbt werden sollte. Schreiben **float**. |
| void [set_Kumimoji](../baseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) override | Bestimmt, ob die Zahlen die textspezifische vertikale Layout-Anordnung für ostasiatische Sprachen ignorieren sollen. Keine Vererbung angewendet. Schreiben [NullableBool](../nullablebool/). |
| void [set_LanguageId](../baseportionformat/set_languageid/)([System::String](../../system/string/)) override | Setzt die Id einer Korrektursprache. Wird für Rechtschreib- und Grammatikprüfung verwendet. Schreiben [System::String](../../system/string/). |
| void [set_LatinFont](../baseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Setzt die lateinischen Schriftinformationen. Null bedeutet, dass die Schriftart undefiniert ist und vom Master ererbt werden sollte. Schreiben [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](../baseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) override | Bestimmt, ob die Höhe eines Textes normalisiert werden soll. Keine Vererbung angewendet. Schreiben [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](../baseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) override | Bestimmt, ob der Text nicht geprüft werden soll. Keine Vererbung angewendet. Schreiben [NullableBool](../nullablebool/). |
| void [set_SmartTagClean](./set_smarttagclean/)(**bool**) override | Bestimmt, ob das Smart-Tag bereinigt werden soll. Keine Vererbung angewendet. Schreiben **bool**. |
| void [set_Spacing](../baseportionformat/set_spacing/)(**float**) override | Setzt die Interzeichenabstandserhöhung. **std::numeric_limits<float>::quiet_NaN()** bedeutet, dass der Wert undefiniert ist und vom Master ererbt werden sollte. Schreiben **float**. |
| void [set_SpellCheck](../baseportionformat/set_spellcheck/)(**bool**) override | Setzt einen Wert, der angibt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. Wenn diese Eigenschaft auf false gesetzt ist, werden Rechtschreibprüfungen für Textelemente unterdrückt. Bei true ist die Rechtschreibprüfung erlaubt. Der Standardwert ist **false**. |
| void [set_StrikethroughType](../baseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | Setzt den Durchstreichungstyp eines Textes. Keine Vererbung angewendet. Schreiben [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](../baseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Setzt die symbolischen Schriftinformationen. Null bedeutet, dass die Schriftart undefiniert ist und vom Master ererbt werden sollte. Schreiben [IFontData](../ifontdata/). |
| void [set_TextCapType](../baseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | Setzt den Typ der Textgroßschreibung. Keine Vererbung angewendet. Schreiben [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines gemeinsam genutzten). Ermöglicht das Umschalten von Zeigern in Containern auf den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Erhält den aktuellen Wert des gemeinsam genutzten Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht die gemeinsam genutzte Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert die gemeinsam genutzte Referenzzählung und gibt sie zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das Sentry-Objekt [LockContext](../../system/lockcontext/) verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Anmerkungen


Diese Klasse wird verwendet, um Formatierungseigenschaften des Textabschnitts zurückzugeben und zu manipulieren, die für den jeweiligen Abschnitt definiert sind. Das bedeutet, dass beim Abrufen von Werten keine Vererbung angewendet wird, sodass Sie in den meisten Fällen Werte erhalten, die "undefiniert" bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich vererbter Werte zu erhalten, müssen Sie die Methode [PortionFormat::GetEffective](./geteffective/) verwenden, die eine [IPortionFormatEffectiveData](../iportionformateffectivedata/)-Instanz zurückgibt.

Das folgende Beispiel zeigt, wie Sie die lateinische Schriftart einem [Paragraph](../paragraph/)-Abschnitt von PowerPoint [Presentation](../presentation/) zuweisen. 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f);

System::SharedPtr<Paragraph> paragraph = System::MakeObject<Paragraph>();
System::SharedPtr<Portion> portion = System::MakeObject<Portion>(u"Theme text format");
paragraph->get_Portions()->Add(portion);
shape->get_TextFrame()->get_Paragraphs()->Add(paragraph);
// Aspose.Slides verwendet diese speziellen Bezeichner (ähnlich wie in PowerPoint verwendet):
// +mn-lt - Körper-Schriftart Lateinisch (kleine lateinische Schriftart)
// +mj-lt - Überschrift-Schriftart Lateinisch (große lateinische Schriftart)
// +mn-ea - Körper-Schriftart Ostasiatisch (kleine ostasiatische Schriftart)
// +mj-ea - Körper-Schriftart Ostasiatisch (kleine ostasiatische Schriftart)
portion->get_PortionFormat()->set_LatinFont(System::MakeObject<FontData>(u"+mn-lt"));
```

## Siehe auch

* Klasse [BasePortionFormat](../baseportionformat/)
* Klasse [IPortionFormat](../iportionformat/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)