---
title: IBasePortionFormat
second_title: Aspose.Slides dla C++ Referencja API
description: Ta klasa zawiera właściwości formatowania części tekstu. W przeciwieństwie do IPortionFormatEffectiveData, wszystkie właściwości tej klasy są zapisywalne.
type: docs
weight: 1457
url: /pl/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat klasa


Ta klasa zawiera właściwości formatowania części tekstu. W przeciwieństwie do [IPortionFormatEffectiveData](../iportionformateffectivedata/), wszystkie właściwości tej klasy są zapisywalne.

```cpp
class IBasePortionFormat : public virtual System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typów referencyjnych w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typów wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | Zwraca Id alternatywnego języka. Odczytaj [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | Zwraca informacje o czcionce skryptu złożonego. Null oznacza, że czcionka jest niezdefiniowana i powinna być odziedziczona po Masterze. Odczytaj [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | Zwraca informacje o czcionce wschodnioazjatyckiej. Null oznacza, że czcionka jest niezdefiniowana i powinna być odziedziczona po Masterze. Odczytaj [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() | Zwraca właściwości tekstu [EffectFormat](../effectformat/). Nie stosuje się dziedziczenia. Tylko do odczytu [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](./get_escapement/)() | Zwraca tekst w indeksie górnym lub dolnym. Wartość od -100 % (indeks dolny) do 100 % (indeks górny). **std::numeric_limits<float>::quiet_NaN()** oznacza, że wartość jest niezdefiniowana i powinna być odziedziczona po Masterze. Odczytaj **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() | Zwraca właściwości tekstu [FillFormat](../fillformat/). Nie stosuje się dziedziczenia. Tylko do odczytu [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() | Określa, czy czcionka jest pogrubiona. Nie stosuje się dziedziczenia. Odczytaj [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](./get_fontheight/)() | Zwraca wysokość czcionki części tekstu. **std::numeric_limits<float>::quiet_NaN()** oznacza, że wysokość jest niezdefiniowana i powinna być odziedziczona po Masterze. Odczytaj **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() | Określa, czy czcionka jest pochylona (italic). Nie stosuje się dziedziczenia. Odczytaj [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | Zwraca typ podkreślenia tekstu. Nie stosuje się dziedziczenia. Odczytaj [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() | Zwraca kolor używany do podświetlania tekstu. Nie stosuje się dziedziczenia. Tylko do odczytu [IColorFormat](../icolorformat/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | Określa, czy styl podkreślenia ma własne właściwości [FillFormat](../fillformat/) czy dziedziczy je z właściwości [FillFormat](../fillformat/) tekstu. Odczytaj [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | Określa, czy styl podkreślenia ma własne właściwości [LineFormat](../lineformat/) czy dziedziczy je z właściwości [LineFormat](../lineformat/) tekstu. Odczytaj [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | Zwraca minimalny rozmiar czcionki, przy którym włącza się kerning. **std::numeric_limits<float>::quiet_NaN()** oznacza, że wartość jest niezdefiniowana i powinna być odziedziczona po Masterze. Odczytaj **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() | Określa, czy liczby powinny ignorować specyficzny dla wschodnich języków układ pionowy tekstu. Nie stosuje się dziedziczenia. Odczytaj [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | Zwraca Id języka korekty. Używany do sprawdzania pisowni i gramatyki. Odczytaj [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | Zwraca informacje o czcionce łacińskiej. Null oznacza, że czcionka jest niezdefiniowana i powinna być odziedziczona po Masterze. Odczytaj [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() | Zwraca właściwości [LineFormat](../lineformat/) dla obramowywania tekstu. Nie stosuje się dziedziczenia. Tylko do odczytu [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() | Określa, czy wysokość tekstu powinna być normalizowana. Nie stosuje się dziedziczenia. Odczytaj [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() | Określa, czy tekst nie powinien być korektowany. Nie stosuje się dziedziczenia. Odczytaj [NullableBool](../nullablebool/). |
| virtual **float** [get_Spacing](./get_spacing/)() | Zwraca przyrost odstępu między znakami. **std::numeric_limits<float>::quiet_NaN()** oznacza, że wartość jest niezdefiniowana i powinna być odziedziczona po Masterze. Odczytaj **float**. |
| virtual **bool** [get_SpellCheck](./get_spellcheck/)() | Zwraca wartość wskazującą, czy sprawdzanie pisowni jest włączone dla części tekstu. Gdy ta właściwość jest ustawiona na false, sprawdzanie pisowni elementów tekstowych jest pomijane. Gdy ustawiona na true, sprawdzanie pisowni jest dozwolone. Domyślna wartość to **false**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | Zwraca typ przekreślenia tekstu. Nie stosuje się dziedziczenia. Odczytaj [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | Zwraca informacje o czcionce symbolicznej. Null oznacza, że czcionka jest niezdefiniowana i powinna być odziedziczona po Masterze. Odczytaj [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | Zwraca typ kapitalizacji tekstu. Nie stosuje się dziedziczenia. Odczytaj [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | Zwraca właściwości linii podkreślenia [FillFormat](../fillformat/). Nie stosuje się dziedziczenia. Tylko do odczytu [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | Zwraca właściwości [LineFormat](../lineformat/) używane do obramowania linii podkreślenia. Nie stosuje się dziedziczenia. Tylko do odczytu [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Zwraca strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie obiektów niestandardowych. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Zwraca rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie typów niestandardowych. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcuchów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| virtual void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) | Ustawia Id alternatywnego języka. Zapisz [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Ustawia informacje o czcionce skryptu złożonego. Null oznacza, że czcionka jest niezdefiniowana i powinna być odziedziczona po Masterze. Zapisz [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Ustawia informacje o czcionce wschodnioazjatyckiej. Null oznacza, że czcionka jest niezdefiniowana i powinna być odziedziczona po Masterze. Zapisz [IFontData](../ifontdata/). |
| virtual void [set_Escapement](./set_escapement/)(**float**) | Ustawia tekst w indeksie górnym lub dolnym. Wartość od -100 % (indeks dolny) do 100 % (indeks górny). **std::numeric_limits<float>::quiet_NaN()** oznacza, że wartość jest niezdefiniowana i powinna być odziedziczona po Masterze. Zapisz **float**. |
| virtual void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) | Określa, czy czcionka jest pogrubiona. Nie stosuje się dziedziczenia. Zapisz [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](./set_fontheight/)(**float**) | Ustawia wysokość czcionki części tekstu. **std::numeric_limits<float>::quiet_NaN()** oznacza, że wysokość jest niezdefiniowana i powinna być odziedziczona po Masterze. Zapisz **float**. |
| virtual void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) | Określa, czy czcionka jest pochylona (italic). Nie stosuje się dziedziczenia. Zapisz [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | Ustawia typ podkreślenia tekstu. Nie stosuje się dziedziczenia. Zapisz [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | Określa, czy styl podkreślenia ma własne właściwości [FillFormat](../fillformat/) czy dziedziczy je z właściwości [FillFormat](../fillformat/) tekstu. Zapisz [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) | Określa, czy styl podkreślenia ma własne właściwości [LineFormat](../lineformat/) czy dziedziczy je z właściwości [LineFormat](../lineformat/) tekstu. Zapisz [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) | Ustawia minimalny rozmiar czcionki, przy którym włącza się kerning. **std::numeric_limits<float>::quiet_NaN()** oznacza, że wartość jest niezdefiniowana i powinna być odziedziczona po Masterze. Zapisz **float**. |
| virtual void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) | Określa, czy liczby powinny ignorować specyficzny dla wschodnich języków pionowy układ tekstu. Nie stosuje się dziedziczenia. Zapisz [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) | Ustawia Id języka korekty. Używany do sprawdzania pisowni i gramatyki. Zapisz [System::String](../../system/string/). |
| virtual void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Ustawia informacje o czcionce łacińskiej. Null oznacza, że czcionka jest niezdefiniowana i powinna być odziedziczona po Masterze. Zapisz [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) | Określa, czy wysokość tekstu powinna być normalizowana. Nie stosuje się dziedziczenia. Zapisz [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) | Określa, czy tekst nie powinien być korektowany. Nie stosuje się dziedziczenia. Zapisz [NullableBool](../nullablebool/). |
| virtual void [set_Spacing](./set_spacing/)(**float**) | Ustawia przyrost odstępu między znakami. **std::numeric_limits<float>::quiet_NaN()** oznacza, że wartość jest niezdefiniowana i powinna być odziedziczona po Masterze. Zapisz **float**. |
| virtual void [set_SpellCheck](./set_spellcheck/)(**bool**) | Ustawia wartość wskazującą, czy sprawdzanie pisowni jest włączone dla części tekstu. Gdy ta właściwość jest ustawiona na false, sprawdzanie pisowni elementów tekstowych jest pomijane. Gdy ustawiona na true, sprawdzanie pisowni jest dozwolone. Domyślna wartość to **false**. |
| virtual void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | Ustawia typ przekreślenia tekstu. Nie stosuje się dziedziczenia. Zapisz [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Ustawia informacje o czcionce symbolicznej. Null oznacza, że czcionka jest niezdefiniowana i powinna być odziedziczona po Masterze. Zapisz [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | Ustawia typ kapitalizacji tekstu. Nie stosuje się dziedziczenia. Zapisz [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala na przełączanie wskaźników w kontenerach do trybu słabego. |
| int [SharedCount](../../system/object/sharedcount/)() const | Zwraca bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie należy wywoływać bezpośrednio; używaj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie należy wywoływać bezpośrednio; używaj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwertowanie obiektów niestandardowych na łańcuch znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowywanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie należy wywoływać bezpośrednio; używaj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie należy wywoływać bezpośrednio; używaj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Uwagi


Ta klasa jest używana do zwracania i modyfikowania właściwości formatowania części tekstu zdefiniowanych dla konkretnej części. Oznacza to, że przy pobieraniu wartości nie jest stosowane dziedziczenie, więc w większości przypadków otrzymasz wartości oznaczające „niezdefiniowane”.

Aby uzyskać efektywne wartości parametrów formatowania, w tym odziedziczone, musisz użyć metody [IPortionFormat::GetEffective](../iportionformat/geteffective/), która zwraca instancję [IPortionFormatEffectiveData](../iportionformateffectivedata/).

## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)