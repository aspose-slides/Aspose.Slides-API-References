---
title: IBasePortionFormat
second_title: Aspose.Sildes dla .NET - Dokumentacja API
description: Ta klasa zawiera właściwości formatowania fragmentu tekstu. W przeciwieństwie do IPortionFormatEffectiveData./iportionformateffectivedata wszystkie właściwości tej klasy są zapisywalne.
type: docs
weight: 5290
url: /pl/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat interfejs

Ta klasa zawiera właściwości formatowania fragmentu tekstu. W przeciwieństwie do [`IPortionFormatEffectiveData`](../iportionformateffectivedata), wszystkie właściwości tej klasy są zapisywalne.

```csharp
public interface IBasePortionFormat
```

## Properties

| Nazwa | Opis |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Zwraca lub ustawia Id alternatywnego języka. Odczyt/zapis String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Zwraca lub ustawia informacje o czcionce dla złożonych skryptów. Null oznacza, że czcionka jest niezdefiniowana i powinna być dziedziczona z Master. Odczyt/zapis [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Zwraca lub ustawia informacje o czcionce wschodnioazjatyckiej. Null oznacza, że czcionka jest niezdefiniowana i powinna być dziedziczona z Master. Odczyt/zapis [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Zwraca właściwości EffectFormat tekstu. Nie stosuje się dziedziczenia. Tylko do odczytu [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Zwraca lub ustawia tekst w indeksie górnym lub dolnym. Wartość od -100% (indeks dolny) do 100% (indeks górny). **float.NaN** oznacza, że wartość jest niezdefiniowana i powinna być dziedziczona z Master. Odczyt/zapis Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Zwraca właściwości FillFormat tekstu. Nie stosuje się dziedziczenia. Tylko do odczytu [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Określa, czy czcionka jest pogrubiona. Nie stosuje się dziedziczenia. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Zwraca lub ustawia wysokość czcionki fragmentu. **float.NaN** oznacza, że wysokość jest niezdefiniowana i powinna być dziedziczona z Master. Odczyt/zapis Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Określa, czy czcionka jest kursywą. Nie stosuje się dziedziczenia. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Zwraca lub ustawia typ podkreślenia tekstu. Nie stosuje się dziedziczenia. Odczyt/zapis [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Zwraca kolor używany do podświetlania tekstu. Nie stosuje się dziedziczenia. Tylko do odczytu [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Określa, czy styl podkreślenia ma własne właściwości FillFormat lub dziedziczy je z właściwości FillFormat tekstu. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Określa, czy styl podkreślenia ma własne właściwości LineFormat lub dziedziczy je z właściwości LineFormat tekstu. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Zwraca lub ustawia minimalny rozmiar czcionki, przy którym powinno być włączone kerning. **float.NaN** oznacza, że wartość jest niezdefiniowana i powinna być dziedziczona z Master. Odczyt/zapis Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Określa, czy liczby powinny ignorować specyficzne dla wschodnich języków układy pionowe tekstu. Nie stosuje się dziedziczenia. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Zwraca lub ustawia Id języka korekty. Używany do sprawdzania pisowni i gramatyki. Odczyt/zapis String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Zwraca lub ustawia informacje o czcionce łacińskiej. Null oznacza, że czcionka jest niezdefiniowana i powinna być dziedziczona z Master. Odczyt/zapis [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Zwraca właściwości LineFormat dla obramowania tekstu. Nie stosuje się dziedziczenia. Tylko do odczytu [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Określa, czy wysokość tekstu powinna być znormalizowana. Nie stosuje się dziedziczenia. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Określa, czy tekst nie powinien być sprawdzany pod kątem korekty. Nie stosuje się dziedziczenia. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Zwraca lub ustawia przyrost odstępu międzyliterowego. **float.NaN** oznacza, że wartość jest niezdefiniowana i powinna być dziedziczona z Master. Odczyt/zapis Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | Zwraca lub ustawia wartość wskazującą, czy sprawdzanie pisowni jest włączone dla fragmentu tekstu. Gdy właściwość jest ustawiona na false, sprawdzanie pisowni elementów tekstowych jest wyłączone. Gdy ustawiona jest na true, sprawdzanie pisowni jest dozwolone. Domyślna wartość to `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Zwraca lub ustawia typ przekreślenia tekstu. Nie stosuje się dziedziczenia. Odczyt/zapis [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Zwraca lub ustawia informacje o czcionce symbolicznej. Null oznacza, że czcionka jest niezdefiniowana i powinna być dziedziczona z Master. Odczyt/zapis [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Zwraca lub ustawia rodzaj kapitalizacji tekstu. Nie stosuje się dziedziczenia. Odczyt/zapis [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Zwraca właściwości FillFormat linii podkreślenia. Nie stosuje się dziedziczenia. Tylko do odczytu [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Zwraca właściwości LineFormat używane do obramowania linii podkreślenia. Nie stosuje się dziedziczenia. Tylko do odczytu [`ILineFormat`](../ilineformat). |

### Uwagi

Ta klasa jest używana do zwracania i manipulowania właściwościami formatowania fragmentu tekstu zdefiniowanymi dla konkretnego fragmentu. Oznacza to, że przy pobieraniu wartości nie jest stosowane dziedziczenie, więc w większości przypadków otrzymasz wartości oznaczające „niezdefiniowane”.

Aby uzyskać skuteczne wartości parametrów formatowania, włączając dziedziczone, należy użyć metody [`GetEffective`](../iportionformat/geteffective), która zwraca instancję [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Zobacz także

* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->