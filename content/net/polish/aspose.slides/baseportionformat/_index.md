---
title: BasePortionFormat
second_title: Aspose.Sildes dla .NET – odniesienie API
description: Wspólne właściwości formatowania fragmentu tekstu.
type: docs
weight: 970
url: /pl/aspose.slides/baseportionformat/
---
## BasePortionFormat klasa

Wspólne właściwości formatowania fragmentu tekstu.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Zwraca lub ustawia identyfikator alternatywnego języka. Odczyt/zapis String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umożliwia pobranie podstawowego interfejsu IPresentationComponent. Tylko do odczytu [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Zwraca lub ustawia informacje o czcionce złożonych skryptów. Null oznacza, że czcionka jest niezdefiniowana i powinna być odziedziczona po Masterze. Odczyt/zapis [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Zwraca lub ustawia informacje o czcionce wschodnioazjatyckiej. Null oznacza, że czcionka jest niezdefiniowana i powinna być odziedziczona po Masterze. Odczyt/zapis [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Zwraca właściwości EffectFormat tekstu. Nie zastosowano dziedziczenia. Tylko do odczytu [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Zwraca lub ustawia tekst w formacie superskriptu lub subskriptu. Wartość od -100% (subskrypt) do 100% (superskrypt). **float.NaN** oznacza, że wartość jest niezdefiniowana i powinna być odziedziczona po Masterze. Odczyt/zapis Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Zwraca właściwości FillFormat tekstu. Nie zastosowano dziedziczenia. Tylko do odczytu [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Określa, czy czcionka jest pogrubiona. Nie zastosowano dziedziczenia. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Zwraca lub ustawia wysokość czcionki fragmentu. **float.NaN** oznacza, że wysokość jest niezdefiniowana i powinna być odziedziczona po Masterze. Odczyt/zapis Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Określa, czy czcionka jest kursywą. Nie zastosowano dziedziczenia. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Zwraca lub ustawia typ podkreślenia tekstu. Nie zastosowano dziedziczenia. Odczyt/zapis [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Zwraca kolor używany do wyróżniania tekstu. Nie zastosowano dziedziczenia. Tylko do odczytu [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Określa, czy styl podkreślenia posiada własne właściwości FillFormat lub dziedziczy je z właściwości FillFormat tekstu. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Określa, czy styl podkreślenia posiada własne właściwości LineFormat lub dziedziczy je z właściwości LineFormat tekstu. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Zwraca lub ustawia minimalny rozmiar czcionki, przy którym powinno być włączone kerning. **float.NaN** oznacza, że wartość jest niezdefiniowana i powinna być odziedziczona po Masterze. Odczyt/zapis Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Określa, czy liczby powinny ignorować specyficzny dla wschodnich języków układ pionowy tekstu. Nie zastosowano dziedziczenia. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Zwraca lub ustawia identyfikator języka korekcyjnego. Używany do sprawdzania pisowni i gramatyki. Odczyt/zapis String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Zwraca lub ustawia informacje o czcionce łacińskiej. Null oznacza, że czcionka jest niezdefiniowana i powinna być odziedziczona po Masterze. Odczyt/zapis [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Zwraca właściwości LineFormat dla obramowania tekstu. Nie zastosowano dziedziczenia. Tylko do odczytu [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Określa, czy wysokość tekstu powinna być znormalizowana. Nie zastosowano dziedziczenia. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Określa, czy tekst nie powinien być sprawdzany pod kątem korekty. Nie zastosowano dziedziczenia. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Zwraca lub ustawia przyrost odstępu między znakami. **float.NaN** oznacza, że wartość jest niezdefiniowana i powinna być odziedziczona po Masterze. Odczyt/zapis Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Pobiera lub ustawia wartość określającą, czy sprawdzanie pisowni jest włączone dla fragmentu tekstu. Gdy właściwość ma wartość false, sprawdzanie pisowni elementów tekstu jest pomijane. Gdy ustawiona jest na true, sprawdzanie pisowni jest dozwolone. Wartość domyślna to `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Zwraca lub ustawia typ przekreślenia tekstu. Nie zastosowano dziedziczenia. Odczyt/zapis [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Zwraca lub ustawia informacje o czcionce symbolicznej. Null oznacza, że czcionka jest niezdefiniowana i powinna być odziedziczona po Masterze. Odczyt/zapis [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Zwraca lub ustawia typ kapitalizacji tekstu. Nie zastosowano dziedziczenia. Odczyt/zapis [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Zwraca właściwości FillFormat linii podkreślenia. Nie zastosowano dziedziczenia. Tylko do odczytu [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Zwraca właściwości LineFormat używane do obramowania linii podkreślenia. Nie zastosowano dziedziczenia. Tylko do odczytu [`ILineFormat`](../ilineformat). |

## Metody

| Nazwa | Opis |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Porównuje z określonym obiektem. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Zwraca kod skrótu. |

### Zobacz także

* klasa [PVIObject](../pviobject)
* interfejs [IBasePortionFormat](../ibaseportionformat)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zbiór [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->