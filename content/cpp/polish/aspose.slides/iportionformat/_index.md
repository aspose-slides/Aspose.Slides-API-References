---
title: IPortionFormat
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Ta klasa zawiera właściwości formatowania fragmentu tekstu. W przeciwieństwie do IPortionFormatEffectiveData, wszystkie właściwości tej klasy są zapisywalne.
type: docs
weight: 3329
url: /pl/aspose.slides/iportionformat/
---
## IPortionFormat klasa

Ta klasa zawiera właściwości formatowania fragmentu tekstu. W przeciwieństwie do [IPortionFormatEffectiveData](../iportionformateffectivedata/), wszystkie właściwości tej klasy są zapisywalne.

```cpp
class IPortionFormat : public virtual Aspose::Slides::IBasePortionFormat,
                       public Aspose::Slides::IHyperlinkContainer
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../ibaseportionformat/get_alternativelanguageid/)() | Zwraca Id alternatywnego języka. Przeczytaj [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() | Zwraca identyfikator zakładki. Przeczytaj [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../ibaseportionformat/get_complexscriptfont/)() | Zwraca informacje o czcionce skryptu złożonego. null oznacza, że czcionka jest niezdefiniowana i powinna być odziedziczona z Mastera. Przeczytaj [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../ibaseportionformat/get_eastasianfont/)() | Zwraca informacje o czcionce wschodnioazjatyckiej. null oznacza, że czcionka jest niezdefiniowana i powinna być odziedziczona z Mastera. Przeczytaj [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ibaseportionformat/get_effectformat/)() | Zwraca właściwości tekstu [EffectFormat](../effectformat/). Nie zastosowano dziedziczenia. Tylko do odczytu [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](../ibaseportionformat/get_escapement/)() | Zwraca tekst w indeksie górnym lub dolnym. Wartość od -100% (indeks dolny) do 100% (indeks górny). **std::numeric_limits<float>::quiet_NaN()** oznacza, że wartość jest niezdefiniowana i powinna być odziedziczona z Mastera. Przeczytaj **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ibaseportionformat/get_fillformat/)() | Zwraca właściwości tekstu [FillFormat](../fillformat/). Nie zastosowano dziedziczenia. Tylko do odczytu [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](../ibaseportionformat/get_fontbold/)() | Określa, czy czcionka jest pogrubiona. Nie zastosowano dziedziczenia. Przeczytaj [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](../ibaseportionformat/get_fontheight/)() | Zwraca wysokość czcionki fragmentu. **std::numeric_limits<float>::quiet_NaN()** oznacza, że wysokość jest niezdefiniowana i powinna być odziedziczona z Mastera. Przeczytaj **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](../ibaseportionformat/get_fontitalic/)() | Określa, czy czcionka jest kursywą. Nie zastosowano dziedziczenia. Przeczytaj [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../ibaseportionformat/get_fontunderline/)() | Zwraca typ podkreślenia tekstu. Nie zastosowano dziedziczenia. Przeczytaj [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../ibaseportionformat/get_highlightcolor/)() | Zwraca kolor używany do podświetlenia tekstu. Nie zastosowano dziedziczenia. Tylko do odczytu [IColorFormat](../icolorformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Zwraca hiperłącze zdefiniowane dla kliknięcia myszy. Przeczytaj [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Menedżer hiperłączy Tylko do odczytu [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Zwraca hiperłącze zdefiniowane dla najechania myszą. Przeczytaj [IHyperlink](../ihyperlink/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../ibaseportionformat/get_ishardunderlinefill/)() | Określa, czy styl podkreślenia ma własne właściwości [FillFormat](../fillformat/) czy dziedziczy je z właściwości [FillFormat](../fillformat/) tekstu. Przeczytaj [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../ibaseportionformat/get_ishardunderlineline/)() | Określa, czy styl podkreślenia ma własne właściwości [LineFormat](../lineformat/) czy dziedziczy je z właściwości [LineFormat](../lineformat/) tekstu. Przeczytaj [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](../ibaseportionformat/get_kerningminimalsize/)() | Zwraca minimalny rozmiar czcionki, przy którym powinno być włączone kerning. **std::numeric_limits<float>::quiet_NaN()** oznacza, że wartość jest niezdefiniowana i powinna być odziedziczona z Mastera. Przeczytaj **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](../ibaseportionformat/get_kumimoji/)() | Określa, czy liczby powinny ignorować pionowy układ tekstu specyficzny dla wschodnich języków. Nie zastosowano dziedziczenia. Przeczytaj [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](../ibaseportionformat/get_languageid/)() | Zwraca Id języka korekty. Używany do sprawdzania pisowni i gramatyki. Przeczytaj [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../ibaseportionformat/get_latinfont/)() | Zwraca informacje o czcionce łacińskiej. null oznacza, że czcionka jest niezdefiniowana i powinna być odziedziczona z Mastera. Przeczytaj [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ibaseportionformat/get_lineformat/)() | Zwraca właściwości [LineFormat](../lineformat/) dla obramowania tekstu. Nie zastosowano dziedziczenia. Tylko do odczytu [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](../ibaseportionformat/get_normaliseheight/)() | Określa, czy wysokość tekstu powinna być znormalizowana. Nie zastosowano dziedziczenia. Przeczytaj [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](../ibaseportionformat/get_proofdisabled/)() | Określa, czy tekst nie powinien być sprawdzany. Nie zastosowano dziedziczenia. Przeczytaj [NullableBool](../nullablebool/). |
| virtual **bool** [get_SmartTagClean](./get_smarttagclean/)() | Określa, czy inteligentny znacznik powinien być wyczyszczony. Nie zastosowano dziedziczenia. Przeczytaj **bool**. |
| virtual **float** [get_Spacing](../ibaseportionformat/get_spacing/)() | Zwraca przyrost odstępu między znakami. **std::numeric_limits<float>::quiet_NaN()** oznacza, że wartość jest niezdefiniowana i powinna być odziedziczona z Mastera. Przeczytaj **float**. |
| virtual **bool** [get_SpellCheck](../ibaseportionformat/get_spellcheck/)() | Zwraca wartość wskazującą, czy sprawdzanie pisowni jest włączone dla fragmentu tekstu. Gdy własność jest ustawiona na false, sprawdzanie pisowni elementów tekstu jest pomijane. Gdy ustawiona na true, sprawdzanie pisowni jest dozwolone. Domyślna wartość to **false**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../ibaseportionformat/get_strikethroughtype/)() | Zwraca typ przekreślenia tekstu. Nie zastosowano dziedziczenia. Przeczytaj [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../ibaseportionformat/get_symbolfont/)() | Zwraca informacje o czcionce symbolicznej. null oznacza, że czcionka jest niezdefiniowana i powinna być odziedziczona z Mastera. Przeczytaj [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../ibaseportionformat/get_textcaptype/)() | Zwraca typ kapitalizacji tekstu. Nie zastosowano dziedziczenia. Przeczytaj [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../ibaseportionformat/get_underlinefillformat/)() | Zwraca właściwości linii podkreślenia [FillFormat](../fillformat/). Nie zastosowano dziedziczenia. Tylko do odczytu [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../ibaseportionformat/get_underlinelineformat/)() | Zwraca właściwości [LineFormat](../lineformat/) używane do obramowania linii podkreślenia. Nie zastosowano dziedziczenia. Tylko do odczytu [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Zwraca strukturę danych licznika referencji powiązaną z obiektem. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() | Zwraca efektywne dane formatowania fragmentu z zastosowanym dziedziczeniem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia hashowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Zwraca rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencją obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o określoną wartość. |
| virtual void [set_AlternativeLanguageId](../ibaseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) | Ustawia Id alternatywnego języka. Zapisz [System::String](../../system/string/). |
| virtual void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) | Ustawia identyfikator zakładki. Zapisz [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](../ibaseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Ustawia informacje o czcionce skryptu złożonego. null oznacza, że czcionka jest niezdefiniowana i powinna być odziedziczona z Mastera. Zapisz [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](../ibaseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Ustawia informacje o czcionce wschodnioazjatyckiej. null oznacza, że czcionka jest niezdefiniowana i powinna być odziedziczona z Mastera. Zapisz [IFontData](../ifontdata/). |
| virtual void [set_Escapement](../ibaseportionformat/set_escapement/)(**float**) | Ustawia tekst w indeksie górnym lub dolnym. Wartość od -100% (indeks dolny) do 100% (indeks górny). **std::numeric_limits<float>::quiet_NaN()** oznacza, że wartość jest niezdefiniowana i powinna być odziedziczona z Mastera. Zapisz **float**. |
| virtual void [set_FontBold](../ibaseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) | Określa, czy czcionka jest pogrubiona. Nie zastosowano dziedziczenia. Zapisz [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](../ibaseportionformat/set_fontheight/)(**float**) | Ustawia wysokość czcionki fragmentu. **std::numeric_limits<float>::quiet_NaN()** oznacza, że wysokość jest niezdefiniowana i powinna być odziedziczona z Mastera. Zapisz **float**. |
| virtual void [set_FontItalic](../ibaseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) | Określa, czy czcionka jest kursywą. Nie zastosowano dziedziczenia. Zapisz [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](../ibaseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | Ustawia typ podkreślenia tekstu. Nie zastosowano dziedziczenia. Zapisz [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Ustawia hiperłącze zdefiniowane dla kliknięcia myszy. Zapisz [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Ustawia hiperłącze zdefiniowane dla najechania myszą. Zapisz [IHyperlink](../ihyperlink/). |
| virtual void [set_IsHardUnderlineFill](../ibaseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | Określa, czy styl podkreślenia ma własne właściwości [FillFormat](../fillformat/) czy dziedziczy je z właściwości [FillFormat](../fillformat/) tekstu. Zapisz [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](../ibaseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) | Określa, czy styl podkreślenia ma własne właściwości [LineFormat](../lineformat/) czy dziedziczy je z właściwości [LineFormat](../lineformat/) tekstu. Zapisz [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](../ibaseportionformat/set_kerningminimalsize/)(**float**) | Ustawia minimalny rozmiar czcionki, przy którym powinno być włączone kerning. **std::numeric_limits<float>::quiet_NaN()** oznacza, że wartość jest niezdefiniowana i powinna być odziedziczona z Mastera. Zapisz **float**. |
| virtual void [set_Kumimoji](../ibaseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) | Określa, czy liczby powinny ignorować pionowy układ tekstu specyficzny dla wschodnich języków. Nie zastosowano dziedziczenia. Zapisz [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](../ibaseportionformat/set_languageid/)([System::String](../../system/string/)) | Ustawia Id języka korekty. Używany do sprawdzania pisowni i gramatyki. Zapisz [System::String](../../system/string/). |
| virtual void [set_LatinFont](../ibaseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Ustawia informacje o czcionce łacińskiej. null oznacza, że czcionka jest niezdefiniowana i powinna być odziedziczona z Mastera. Zapisz [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](../ibaseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) | Określa, czy wysokość tekstu powinna być znormalizowana. Nie zastosowano dziedziczenia. Zapisz [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](../ibaseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) | Określa, czy tekst nie powinien być sprawdzany. Nie zastosowano dziedziczenia. Zapisz [NullableBool](../nullablebool/). |
| virtual void [set_SmartTagClean](./set_smarttagclean/)(**bool**) | Określa, czy inteligentny znacznik powinien być wyczyszczony. Nie zastosowano dziedziczenia. Zapisz **bool**. |
| virtual void [set_Spacing](../ibaseportionformat/set_spacing/)(**float**) | Ustawia przyrost odstępu między znakami. **std::numeric_limits<float>::quiet_NaN()** oznacza, że wartość jest niezdefiniowana i powinna być odziedziczona z Mastera. Zapisz **float**. |
| virtual void [set_SpellCheck](../ibaseportionformat/set_spellcheck/)(**bool**) | Ustawia wartość wskazującą, czy sprawdzanie pisowni jest włączone dla fragmentu tekstu. Gdy własność jest ustawiona na false, sprawdzanie pisowni elementów tekstu jest pomijane. Gdy ustawiona na true, sprawdzanie pisowni jest dozwolone. Domyślna wartość to **false**. |
| virtual void [set_StrikethroughType](../ibaseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | Ustawia typ przekreślenia tekstu. Nie zastosowano dziedziczenia. Zapisz [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](../ibaseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Ustawia informacje o czcionce symbolicznej. null oznacza, że czcionka jest niezdefiniowana i powinna być odziedziczona z Mastera. Zapisz [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](../ibaseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | Ustawia typ kapitalizacji tekstu. Nie zastosowano dziedziczenia. Zapisz [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Zwraca bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do łańcucha znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Uwagi

Ta klasa jest używana do zwracania i manipulowania właściwościami formatowania fragmentu tekstu zdefiniowanymi dla konkretnego fragmentu. Oznacza to, że przy pobieraniu wartości nie stosowane jest dziedziczenie, więc w większości przypadków otrzymasz wartości oznaczające „niezdefiniowane”.

Aby uzyskać efektywne wartości parametrów formatowania wraz z dziedziczonymi, należy użyć metody [IPortionFormat::GetEffective](./geteffective/), która zwraca instancję [IPortionFormatEffectiveData](../iportionformateffectivedata/).

## Zobacz także

* Klasa [IBasePortionFormat](../ibaseportionformat/)
* Klasa [IHyperlinkContainer](../ihyperlinkcontainer/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)