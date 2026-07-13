---
title: LineFormat
second_title: Aspose.Slides dla Androida przy użyciu Java API
description: Reprezentuje format linii.
type: docs
url: /pl/com.aspose.slides/lineformat/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ILineFormat](../../com.aspose.slides/ilineformat)
```
public final class LineFormat extends PVIObject implements ILineFormat
```

Reprezentuje format linii.
## Metody

| Metoda | Opis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isFormatNotDefined()](#isFormatNotDefined--) | Zwraca true, jeśli format linii nie jest określony (tak jak po utworzeniu, domyślnie). |
| [getFillFormat()](#getFillFormat--) | Zwraca format wypełnienia linii. |
| [getSketchFormat()](#getSketchFormat--) | Zwraca format szkicu linii. |
| [getWidth()](#getWidth--) | Zwraca lub ustawia szerokość linii. |
| [setWidth(double value)](#setWidth-double-) | Zwraca lub ustawia szerokość linii. |
| [getDashStyle()](#getDashStyle--) | Zwraca lub ustawia styl kreski linii. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Zwraca lub ustawia styl kreski linii. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Zwraca lub ustawia niestandardowy wzorzec kreski. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Zwraca lub ustawia niestandardowy wzorzec kreski. |
| [getCapStyle()](#getCapStyle--) | Zwraca lub ustawia styl zakończenia linii. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Zwraca lub ustawia styl zakończenia linii. |
| [getStyle()](#getStyle--) | Zwraca lub ustawia styl linii. |
| [setStyle(byte value)](#setStyle-byte-) | Zwraca lub ustawia styl linii. |
| [getAlignment()](#getAlignment--) | Zwraca lub ustawia wyrównanie linii. |
| [setAlignment(byte value)](#setAlignment-byte-) | Zwraca lub ustawia wyrównanie linii. |
| [getJoinStyle()](#getJoinStyle--) | Zwraca lub ustawia styl łączenia linii. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Zwraca lub ustawia styl łączenia linii. |
| [getMiterLimit()](#getMiterLimit--) | Zwraca lub ustawia limit fazy linii. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Zwraca lub ustawia limit fazy linii. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Zwraca lub ustawia styl grotu strzały na początku linii. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Zwraca lub ustawia styl grotu strzały na początku linii. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Zwraca lub ustawia styl grotu strzały na końcu linii. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Zwraca lub ustawia styl grotu strzały na końcu linii. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Zwraca lub ustawia szerokość grotu strzały na początku linii. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Zwraca lub ustawia szerokość grotu strzały na początku linii. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Zwraca lub ustawia szerokość grotu strzały na końcu linii. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Zwraca lub ustawia szerokość grotu strzały na końcu linii. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Zwraca lub ustawia długość grotu strzały na początku linii. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Zwraca lub ustawia długość grotu strzały na początku linii. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Zwraca lub ustawia długość grotu strzały na końcu linii. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Zwraca lub ustawia długość grotu strzały na końcu linii. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Określa, czy dwa obiekty LineFormat są równe. |
| [getEffective()](#getEffective--) | Pobiera efektywne dane formatowania linii z zastosowanym dziedziczeniem. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Wersja. Tylko do odczytu long.

**Zwraca:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Porównuje z określonym obiektem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Zwraca:**
boolean
### isFormatNotDefined() {#isFormatNotDefined--}
```
public final boolean isFormatNotDefined()
```


Zwraca true, jeśli format linii nie jest określony (tak jak po utworzeniu, domyślnie). Tylko do odczytu  boolean .

**Zwraca:**
boolean
### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```


Zwraca format wypełnienia linii. Tylko do odczytu [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Zwraca:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)
### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```


Zwraca format szkicu linii. Tylko do odczytu [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Zwraca:**
[ISketchFormat](../../com.aspose.slides/isketchformat)
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Zwraca lub ustawia szerokość linii. Odczyt/zapis  double .

**Zwraca:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Zwraca lub ustawia szerokość linii. Odczyt/zapis  double .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |
### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```


Zwraca lub ustawia styl kreski linii. Odczyt/zapis [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Zwraca:**
byte
### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```


Zwraca lub ustawia styl kreski linii. Odczyt/zapis [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```


Zwraca lub ustawia niestandardowy wzorzec kreski. Odczyt/zapis  float[] .

**Zwraca:**
float[]
### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```


Zwraca lub ustawia niestandardowy wzorzec kreski. Odczyt/zapis  float[] .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float[] |  |
### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```


Zwraca lub ustawia styl zakończenia linii. Odczyt/zapis [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Zwraca:**
byte
### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```


Zwraca lub ustawia styl zakończenia linii. Odczyt/zapis [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getStyle() {#getStyle--}
```
public final byte getStyle()
```


Zwraca lub ustawia styl linii. Odczyt/zapis [LineStyle](../../com.aspose.slides/linestyle).

**Zwraca:**
byte
### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```


Zwraca lub ustawia styl linii. Odczyt/zapis [LineStyle](../../com.aspose.slides/linestyle).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```


Zwraca lub ustawia wyrównanie linii. Odczyt/zapis [LineAlignment](../../com.aspose.slides/linealignment).

**Zwraca:**
byte
### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```


Zwraca lub ustawia wyrównanie linii. Odczyt/zapis [LineAlignment](../../com.aspose.slides/linealignment).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```


Zwraca lub ustawia styl łączenia linii. Odczyt/zapis [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Zwraca:**
byte
### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```


Zwraca lub ustawia styl łączenia linii. Odczyt/zapis [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```


Zwraca lub ustawia limit fazy linii. Odczyt/zapis  float .

**Zwraca:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```


Zwraca lub ustawia limit fazy linii. Odczyt/zapis  float .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```


Zwraca lub ustawia styl grotu strzały na początku linii. Odczyt/zapis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Zwraca:**
byte
### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```


Zwraca lub ustawia styl grotu strzały na początku linii. Odczyt/zapis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```


Zwraca lub ustawia styl grotu strzały na końcu linii. Odczyt/zapis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Zwraca:**
byte
### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```


Zwraca lub ustawia styl grotu strzały na końcu linii. Odczyt/zapis [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```


Zwraca lub ustawia szerokość grotu strzały na początku linii. Odczyt/zapis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Zwraca:**
byte
### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```


Zwraca lub ustawia szerokość grotu strzały na początku linii. Odczyt/zapis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```


Zwraca lub ustawia szerokość grotu strzały na końcu linii. Odczyt/zapis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Zwraca:**
byte
### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```


Zwraca lub ustawia szerokość grotu strzały na końcu linii. Odczyt/zapis [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```


Zwraca lub ustawia długość grotu strzały na początku linii. Odczyt/zapis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Zwraca:**
byte
### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```


Zwraca lub ustawia długość grotu strzały na początku linii. Odczyt/zapis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```


Zwraca lub ustawia długość grotu strzały na końcu linii. Odczyt/zapis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Zwraca:**
byte
### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```


Zwraca lub ustawia długość grotu strzały na końcu linii. Odczyt/zapis [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
```


Określa, czy dwa obiekty LineFormat są równe.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | LineFormat do porównania z bieżącym LineFormat. |

**Zwraca:**
boolean - **true**, jeśli określony LineFormat jest równy bieżącemu LineFormat; w przeciwnym razie **false**.
### getEffective() {#getEffective--}
```
public final ILineFormatEffectiveData getEffective()
```


Pobiera efektywne dane formatowania linii z zastosowanym dziedziczeniem.

--------------------

> ```
> This example demonstrates getting shape's effective line format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	ILineFormatEffectiveData effectiveLineFormat = pres.getSlides().get_Item(0).getShapes().get_Item(0).getLineFormat().getEffective();
>  	System.out.println("Style: " + effectiveLineFormat.getStyle());
>  	System.out.println("Width: " + effectiveLineFormat.getWidth());
>  	System.out.println("Fill type: " + effectiveLineFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).