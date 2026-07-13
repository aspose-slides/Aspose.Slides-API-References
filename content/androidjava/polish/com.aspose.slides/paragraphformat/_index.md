---
title: ParagraphFormat
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Ta klasa zawiera właściwości formatowania akapitu.
type: docs
url: /pl/com.aspose.slides/paragraphformat/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

Ta klasa zawiera właściwości formatowania akapitu. W przeciwieństwie do [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata), wszystkie właściwości tej klasy są zapisywalne.

--------------------

Ta klasa służy do zwracania i manipulowania właściwościami formatowania akapitu zdefiniowanymi dla konkretnego akapitu. Oznacza to, że przy pobieraniu wartości nie jest stosowane dziedziczenie, więc w większości przypadków otrzymasz wartości oznaczające „niezdefiniowane”.

Aby uzyskać skuteczne wartości parametrów formatowania, w tym odziedziczone, musisz użyć metody [getEffective](../../com.aspose.slides/paragraphformat\#getEffective), która zwraca instancję [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

## Konstruktorzy

| Konstruktor | Opis |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | Inicjalizuje nową instancję klasy [ParagraphFormat](../../com.aspose.slides/paragraphformat). |

## Metody

| Metoda | Opis |
| --- | --- |
| [getBullet()](#getBullet--) | Zwraca format wypunktowania akapitu. |
| [getDepth()](#getDepth--) | Zwraca lub ustawia głębokość akapitu. |
| [setDepth(short value)](#setDepth-short-) | Zwraca lub ustawia głębokość akapitu. |
| [getAlignment()](#getAlignment--) | Zwraca lub ustawia wyrównanie tekstu w akapicie bez dziedziczenia. |
| [setAlignment(int value)](#setAlignment-int-) | Zwraca lub ustawia wyrównanie tekstu w akapicie bez dziedziczenia. |
| [getSpaceWithin()](#getSpaceWithin--) | Zwraca lub ustawia ilość odstępu między liniami bazowymi w akapicie. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Zwraca lub ustawia ilość odstępu między liniami bazowymi w akapicie. |
| [getSpaceBefore()](#getSpaceBefore--) | Zwraca lub ustawia ilość odstępu przed pierwszą linią w akapicie bez dziedziczenia. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Zwraca lub ustawia ilość odstępu przed pierwszą linią w akapicie bez dziedziczenia. |
| [getSpaceAfter()](#getSpaceAfter--) | Zwraca lub ustawia ilość odstępu po ostatniej linii w akapicie bez dziedziczenia. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Zwraca lub ustawia ilość odstępu po ostatniej linii w akapicie bez dziedziczenia. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Określa, czy w akapicie używany jest podział linii w stylu wschodnioazjatyckim. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Określa, czy w akapicie używany jest podział linii w stylu wschodnioazjatyckim. |
| [getRightToLeft()](#getRightToLeft--) | Określa, czy w akapicie używany jest zapis od prawej do lewej. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Określa, czy w akapicie używany jest zapis od prawej do lewej. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Określa, czy w akapicie używany jest podział linii łaciński. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Określa, czy w akapicie używany jest podział linii łaciński. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Określa, czy w akapicie używana jest wisząca interpunkcja. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Określa, czy w akapicie używana jest wisząca interpunkcja. |
| [getMarginLeft()](#getMarginLeft--) | Zwraca lub ustawia lewy margines w akapicie bez dziedziczenia. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Zwraca lub ustawia lewy margines w akapicie bez dziedziczenia. |
| [getMarginRight()](#getMarginRight--) | Zwraca lub ustawia prawy margines w akapicie bez dziedziczenia. |
| [setMarginRight(float value)](#setMarginRight-float-) | Zwraca lub ustawia prawy margines w akapicie bez dziedziczenia. |
| [getIndent()](#getIndent--) | Zwraca lub ustawia wcięcie pierwszej linii/odwieszenie akapitu bez dziedziczenia. |
| [setIndent(float value)](#setIndent-float-) | Zwraca lub ustawia wcięcie pierwszej linii/odwieszenie akapitu bez dziedziczenia. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Zwraca lub ustawia domyślny rozmiar tabulacji bez dziedziczenia. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Zwraca lub ustawia domyślny rozmiar tabulacji bez dziedziczenia. |
| [getTabs()](#getTabs--) | Zwraca tabulacje akapitu. |
| [getFontAlignment()](#getFontAlignment--) | Zwraca lub ustawia wyrównanie czcionki w akapicie bez dziedziczenia. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Zwraca lub ustawia wyrównanie czcionki w akapicie bez dziedziczenia. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Zwraca domyślny format fragmentu akapitu. |
| [getEffective()](#getEffective--) | Pobiera skuteczne dane formatowania akapitu z zastosowanym dziedziczeniem. |
| [getVersion()](#getVersion--) |  |

### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```

Inicjalizuje nową instancję klasy [ParagraphFormat](../../com.aspose.slides/paragraphformat).

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```

Zwraca format wypunktowania akapitu. Tylko do odczytu [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Zwraca:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public final short getDepth()
```

Zwraca lub ustawia głębokość akapitu. Wartość 0 oznacza wartość niezdefiniowaną. Odczyt/zapis  short .

**Zwraca:**
short

### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```

Zwraca lub ustawia głębokość akapitu. Wartość 0 oznacza wartość niezdefiniowaną. Odczyt/zapis  short .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

Zwraca lub ustawia wyrównanie tekstu w akapicie bez dziedziczenia. Odczyt/zapis [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Utwórz obiekt Presentation reprezentujący plik PPTX
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Uzyskiwanie pierwszego slajdu
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Uzyskiwanie pierwszego i drugiego placeholdera na slajdzie oraz rzutowanie na AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Zmienianie tekstu w obu placeholderach
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Pobieranie pierwszego akapitu placeholderów
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Wyrównywanie akapitu tekstu do środka
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //Zapisywanie prezentacji jako plik PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

Zwraca lub ustawia wyrównanie tekstu w akapicie bez dziedziczenia. Odczyt/zapis [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Utwórz obiekt Presentation reprezentujący plik PPTX
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Uzyskiwanie pierwszego slajdu
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Uzyskiwanie pierwszego i drugiego placeholdera na slajdzie oraz rzutowanie na AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Zmienianie tekstu w obu placeholderach
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Pobieranie pierwszego akapitu placeholderów
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Wyrównywanie akapitu tekstu do środka
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //Zapisywanie prezentacji jako plik PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```

Zwraca lub ustawia ilość odstępu między liniami bazowymi w akapicie. Wartość dodatnia oznacza procent, ujemna – rozmiar w punktach. Dziedziczenie nie jest stosowane. Odczyt/zapis  float .

**Zwraca:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```

Zwraca lub ustawia ilość odstępu między liniami bazowymi w akapicie. Wartość dodatnia oznacza procent, ujemna – rozmiar w punktach. Dziedziczenie nie jest stosowane. Odczyt/zapis  float .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```

Zwraca lub ustawia ilość odstępu przed pierwszą linią w akapicie bez dziedziczenia. Wartość dodatnia określa procent rozmiaru czcionki, jaką ma zajmować biały odstęp. Wartość ujemna określa rozmiar białego odstępu w punktach. Odczyt/zapis  float .

**Zwraca:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```

Zwraca lub ustawia ilość odstępu przed pierwszą linią w akapicie bez dziedziczenia. Wartość dodatnia określa procent rozmiaru czcionki, jaką ma zajmować biały odstęp. Wartość ujemna określa rozmiar białego odstępu w punktach. Odczyt/zapis  float .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```

Zwraca lub ustawia ilość odstępu po ostatniej linii w akapicie bez dziedziczenia. Wartość dodatnia określa procent rozmiaru czcionki, jaką ma zajmować biały odstęp. Wartość ujemna określa rozmiar białego odstępu w punktach. Odczyt/zapis  float .

**Zwraca:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```

Zwraca lub ustawia ilość odstępu po ostatniej linii w akapicie bez dziedziczenia. Wartość dodatnia określa procent rozmiaru czcionki, jaką ma zajmować biały odstęp. Wartość ujemna określa rozmiar białego odstępu w punktach. Odczyt/zapis  float .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```

Określa, czy w akapicie używany jest podział linii w stylu wschodnioazjatyckim. Dziedziczenie nie jest stosowane. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```

Określa, czy w akapicie używany jest podział linii w stylu wschodnioazjatyckim. Dziedziczenie nie jest stosowane. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```

Określa, czy w akapicie używany jest zapis od prawej do lewej. Dziedziczenie nie jest stosowane. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```

Określa, czy w akapicie używany jest zapis od prawej do lewej. Dziedziczenie nie jest stosowane. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```

Określa, czy w akapicie używany jest podział linii łaciński. Dziedziczenie nie jest stosowane. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```

Określa, czy w akapicie używany jest podział linii łaciński. Dziedziczenie nie jest stosowane. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```

Określa, czy w akapicie używana jest wisząca interpunkcja. Dziedziczenie nie jest stosowane. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```

Określa, czy w akapicie używana jest wisząca interpunkcja. Dziedziczenie nie jest stosowane. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```

Zwraca lub ustawia lewy margines w akapicie bez dziedziczenia. Odczyt/zapis  float .

**Zwraca:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```

Zwraca lub ustawia lewy margines w akapicie bez dziedziczenia. Odczyt/zapis  float .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```

Zwraca lub ustawia prawy margines w akapicie bez dziedziczenia. Odczyt/zapis  float .

**Zwraca:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```

Zwraca lub ustawia prawy margines w akapicie bez dziedziczenia. Odczyt/zapis  float .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public final float getIndent()
```

Zwraca lub ustawia wcięcie pierwszej linii/odwieszenie akapitu bez dziedziczenia. Odwieszenie może być określone wartością ujemną. Odczyt/zapis  float .

**Zwraca:**
float

### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```

Zwraca lub ustawia wcięcie pierwszej linii/odwieszenie akapitu bez dziedziczenia. Odwieszenie może być określone wartością ujemną. Odczyt/zapis  float .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```

Zwraca lub ustawia domyślny rozmiar tabulacji bez dziedziczenia. Odczyt/zapis  float .

**Zwraca:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```

Zwraca lub ustawia domyślny rozmiar tabulacji bez dziedziczenia. Odczyt/zapis  float .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```

Zwraca tabulacje akapitu. Dziedziczenie nie jest stosowane. Tylko do odczytu [ITabCollection](../../com.aspose.slides/itabcollection).

**Zwraca:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```

Zwraca lub ustawia wyrównanie czcionki w akapicie bez dziedziczenia. Odczyt/zapis [FontAlignment](../../com.aspose.slides/fontalignment).

**Zwraca:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```

Zwraca lub ustawia wyrównanie czcionki w akapicie bez dziedziczenia. Odczyt/zapis [FontAlignment](../../com.aspose.slides/fontalignment).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```

Zwraca domyślny format fragmentu akapitu. Dziedziczenie nie jest stosowane. Tylko do odczytu [IPortionFormat](../../com.aspose.slides/iportionformat).

**Zwraca:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```

Pobiera skuteczne dane formatowania akapitu z zastosowanym dziedziczeniem.

--------------------

> ```
> This example demonstrates getting some effective paragraph format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IParagraphFormatEffectiveData effectiveParagraphFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getEffective();
>  	System.out.println("Text alignment: " + effectiveParagraphFormat.getAlignment());
>  	System.out.println("Indent: " + effectiveParagraphFormat.getIndent());
>  	System.out.println("Bullet type: " + effectiveParagraphFormat.getBullet().getType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Wersja. Tylko do odczytu long.

**Zwraca:**
long