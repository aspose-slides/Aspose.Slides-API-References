---
title: PortionFormat
second_title: Aspose.Sildes dla .NET – Dokumentacja API
description: Ta klasa zawiera właściwości formatowania fragmentu tekstu. W przeciwieństwie do IPortionFormatEffectiveData./iportionformateffectivedata wszystkie właściwości tej klasy są zapisywalne.
type: docs
weight: 9470
url: /pl/aspose.slides/portionformat/
---
## PortionFormat klasa

Ta klasa zawiera właściwości formatowania fragmentu tekstu. W przeciwieństwie do [`IPortionFormatEffectiveData`](../iportionformateffectivedata), wszystkie właściwości tej klasy są zapisywalne.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## Konstruktory

| Name | Description |
| --- | --- |
| [PortionFormat](portionformat)() | Inicjalizuje nową instancję klasy [`PortionFormat`](../portionformat). |

## Właściwości

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Zwraca lub ustawia Id alternatywnego języka. Odczyt/zapis String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umożliwia uzyskanie podstawowego interfejsu IPresentationComponent. Tylko do odczytu [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Zwraca lub ustawia identyfikator zakładki. Odczyt/zapis String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Zwraca lub ustawia informacje o czcionce skryptu złożonego. Null oznacza, że czcionka jest nieokreślona i powinna być dziedziczona po Masterze. Odczyt/zapis [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Zwraca lub ustawia informacje o czcionce wschodnioazjatyckiej. Null oznacza, że czcionka jest nieokreślona i powinna być dziedziczona po Masterze. Odczyt/zapis [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Zwraca właściwości EffectFormat tekstu. Nie stosuje się dziedziczenia. Tylko do odczytu [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Zwraca lub ustawia tekst w indeksie górnym lub dolnym. Wartość od -100% (indeks dolny) do 100% (indeks górny). **float.NaN** oznacza, że wartość jest nieokreślona i powinna być dziedziczona po Masterze. Odczyt/zapis Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Zwraca właściwości FillFormat tekstu. Nie stosuje się dziedziczenia. Tylko do odczytu [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Określa, czy czcionka jest pogrubiona. Nie stosuje się dziedziczenia. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Zwraca lub ustawia wysokość czcionki fragmentu. **float.NaN** oznacza, że wysokość jest nieokreślona i powinna być dziedziczona po Masterze. Odczyt/zapis Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Określa, czy czcionka jest pochyła. Nie stosuje się dziedziczenia. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Zwraca lub ustawia typ podkreślenia tekstu. Nie stosuje się dziedziczenia. Odczyt/zapis [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Zwraca kolor używany do podświetlenia tekstu. Nie stosuje się dziedziczenia. Tylko do odczytu [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Zwraca lub ustawia hiperłącze zdefiniowane dla kliknięcia myszy. Odczyt/zapis [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Menedżer hiperłączy. Tylko do odczytu [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Zwraca lub ustawia hiperłącze zdefiniowane dla najechania myszą. Odczyt/zapis [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Określa, czy styl podkreślenia ma własne właściwości FillFormat lub dziedziczy je z właściwości FillFormat tekstu. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Określa, czy styl podkreślenia ma własne właściwości LineFormat lub dziedziczy je z właściwości LineFormat tekstu. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Zwraca lub ustawia minimalny rozmiar czcionki, przy którym ma być włączone kerning. **float.NaN** oznacza, że wartość jest nieokreślona i powinna być dziedziczona po Masterze. Odczyt/zapis Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Określa, czy liczby mają ignorować wschodniojęzykowy specyficzny układ pionowy tekstu. Nie stosuje się dziedziczenia. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Zwraca lub ustawia Id języka korekty. Używany do sprawdzania pisowni i gramatyki. Odczyt/zapis String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Zwraca lub ustawia informacje o czcionce łacińskiej. Null oznacza, że czcionka jest nieokreślona i powinna być dziedziczona po Masterze. Odczyt/zapis [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Zwraca właściwości LineFormat dla konturu tekstu. Nie stosuje się dziedziczenia. Tylko do odczytu [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Określa, czy wysokość tekstu ma być normalizowana. Nie stosuje się dziedziczenia. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Określa, czy tekst nie powinien być sprawdzany. Nie stosuje się dziedziczenia. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Określa, czy inteligentny znacznik ma być usunięty. Nie stosuje się dziedziczenia. Odczyt/zapis Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Zwraca lub ustawia przyrost odstępu między znakami. **float.NaN** oznacza, że wartość jest nieokreślona i powinna być dziedziczona po Masterze. Odczyt/zapis Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Pobiera lub ustawia wartość wskazującą, czy sprawdzanie pisowni jest włączone dla fragmentu tekstu. Gdy właściwość jest ustawiona na false, sprawdzanie pisowni elementów tekstowych jest pomijane. Gdy ustawiona na true, sprawdzanie pisowni jest dozwolone. Domyślna wartość to `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Zwraca lub ustawia typ przekreślenia tekstu. Nie stosuje się dziedziczenia. Odczyt/zapis [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Zwraca lub ustawia informacje o czcionce symbolicznej. Null oznacza, że czcionka jest nieokreślona i powinna być dziedziczona po Masterze. Odczyt/zapis [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Zwraca lub ustawia typ kapitalizacji tekstu. Nie stosuje się dziedziczenia. Odczyt/zapis [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Zwraca właściwości FillFormat linii podkreślenia. Nie stosuje się dziedziczenia. Tylko do odczytu [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Zwraca właściwości LineFormat używane do obramowania linii podkreślenia. Nie stosuje się dziedziczenia. Tylko do odczytu [`ILineFormat`](../ilineformat). |

## Metody

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Porównuje z określonym obiektem. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Pobiera efektywne dane formatowania fragmentu z zastosowanym dziedziczeniem. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Zwraca kod skrótu. |

### Uwagi

Ta klasa służy do zwracania i manipulowania właściwościami formatowania fragmentu tekstu zdefiniowanymi dla konkretnego fragmentu. Oznacza to, że przy pobieraniu wartości nie stosuje się dziedziczenia, więc w większości przypadków otrzymasz wartości oznaczające „niezdefiniowane”.

Aby uzyskać efektywne wartości parametrów formatowania, w tym dziedziczone, należy użyć metody [`GetEffective`](./geteffective), która zwraca instancję [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Przykłady

Poniższy przykład pokazuje, jak przypisać czcionkę łacińską do fragmentu akapitu w prezentacji PowerPoint.

```csharp
[C#]
//Utwórz obiekt prezentacji, który reprezentuje plik prezentacji
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides używa tych specjalnych identyfikatorów (podobnych do używanych w PowerPoint):
// +mn-lt - Czcionka ciała Łacińska (Mniejsza czcionka łacińska)
// +mj-lt - Czcionka nagłówka Łacińska (Główna czcionka łacińska)
// +mn-ea - Czcionka ciała wschodnioazjatycka (Mniejsza czcionka wschodnioazjatycka)
// +mj-ea - Czcionka ciała wschodnioazjatycka (Mniejsza czcionka wschodnioazjatycka)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Zobacz także

* klasa [BasePortionFormat](../baseportionformat)
* interfejs [IPortionFormat](../iportionformat)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->