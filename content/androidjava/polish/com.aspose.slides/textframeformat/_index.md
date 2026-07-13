---
title: TextFrameFormat
second_title: Aspose.Slides dla Androida poprzez odwołanie API Java
description: Zawiera właściwości formatTextFrameFormatting TextFrames.
type: docs
url: /pl/com.aspose.slides/textframeformat/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

Zawiera właściwości formatTextFrameFormatting ramki TextFrame.
## Konstruktorzy

| Konstruktor | Opis |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | Inicjalizuje nową instancję klasy [TextFrameFormat](../../com.aspose.slides/textframeformat). |
## Metody

| Metoda | Opis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | Zwraca styl tekstu. |
| [getThreeDFormat()](#getThreeDFormat--) | Zwraca obiekt ThreeDFormat, który reprezentuje właściwości efektu 3D dla tekstu. |
| [getMarginLeft()](#getMarginLeft--) | Zwraca lub ustawia lewy margines (punkty) w TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Zwraca lub ustawia lewy margines (punkty) w TextFrame. |
| [getMarginRight()](#getMarginRight--) | Zwraca lub ustawia prawy margines (punkty) w TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Zwraca lub ustawia prawy margines (punkty) w TextFrame. |
| [getMarginTop()](#getMarginTop--) | Zwraca lub ustawia górny margines (punkty) w TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Zwraca lub ustawia górny margines (punkty) w TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Zwraca lub ustawia dolny margines (punkty) w TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Zwraca lub ustawia dolny margines (punkty) w TextFrame. |
| [getWrapText()](#getWrapText--) | Prawda, jeśli tekst jest zawijany przy marginesach TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | Prawda, jeśli tekst jest zawijany przy marginesach TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Zwraca lub ustawia pionowy tekst kotwiczenia w TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Zwraca lub ustawia pionowy tekst kotwiczenia w TextFrame. |
| [getCenterText()](#getCenterText--) | Jeśli NullableBool.True, tekst powinien być wyśrodkowany w poziomie w ramce. |
| [setCenterText(byte value)](#setCenterText-byte-) | Jeśli NullableBool.True, tekst powinien być wyśrodkowany w poziomie w ramce. |
| [getTextVerticalType()](#getTextVerticalType--) | Określa orientację tekstu. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Określa orientację tekstu. |
| [getAutofitType()](#getAutofitType--) | Zwraca lub ustawia tryb dopasowania automatycznego tekstu. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Zwraca lub ustawia tryb dopasowania automatycznego tekstu. |
| [getColumnCount()](#getColumnCount--) | Zwraca lub ustawia liczbę kolumn w obszarze tekstu. |
| [setColumnCount(int value)](#setColumnCount-int-) | Zwraca lub ustawia liczbę kolumn w obszarze tekstu. |
| [getColumnSpacing()](#getColumnSpacing--) | Zwraca lub ustawia odstęp pomiędzy kolumnami tekstu w obszarze tekstu (w punktach). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Zwraca lub ustawia odstęp pomiędzy kolumnami tekstu w obszarze tekstu (w punktach). |
| [getRotationAngle()](#getRotationAngle--) | Określa niestandardowy obrót stosowany do tekstu w obrębie ramki. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Określa niestandardowy obrót stosowany do tekstu w obrębie ramki. |
| [getTransform()](#getTransform--) | Pobiera lub ustawia kształt zawijania tekstu. |
| [setTransform(byte value)](#setTransform-byte-) | Pobiera lub ustawia kształt zawijania tekstu. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Pobiera lub ustawia utrzymanie płaskości tekstu nawet po zastosowaniu efektu obrotu 3D. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Pobiera lub ustawia utrzymanie płaskości tekstu nawet po zastosowaniu efektu obrotu 3D. |
| [getEffective()](#getEffective--) | Pobiera efektywne dane formatowania ramki tekstowej z uwzględnionym dziedziczeniem. |
### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```


Inicjalizuje nową instancję klasy [TextFrameFormat](../../com.aspose.slides/textframeformat).

### getVersion() {#getVersion--}
```
public long getVersion()
```


Wersja. Tylko do odczytu long.

**Zwraca:**
long
### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```


Zwraca styl tekstu. Tylko do odczytu [ITextStyle](../../com.aspose.slides/itextstyle).

**Zwraca:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```


Zwraca obiekt ThreeDFormat, który reprezentuje właściwości efektu 3D dla tekstu. Tylko do odczytu [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Ustaw przekształcenie tekstu
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // Ustaw ekstruzję
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // Ustaw kontur
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // Ustaw głębokość
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // Ustaw materiał
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // Ustaw oświetlenie
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // Ustaw typ kamery
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```


Zwraca lub ustawia lewy margines (punkty) w TextFrame. Odczyt/zapis double.

**Zwraca:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```


Zwraca lub ustawia lewy margines (punkty) w TextFrame. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```


Zwraca lub ustawia prawy margines (punkty) w TextFrame. Odczyt/zapis double.

**Zwraca:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```


Zwraca lub ustawia prawy margines (punkty) w TextFrame. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```


Zwraca lub ustawia górny margines (punkty) w TextFrame. Odczyt/zapis double.

**Zwraca:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```


Zwraca lub ustawia górny margines (punkty) w TextFrame. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```


Zwraca lub ustawia dolny margines (punkty) w TextFrame. Odczyt/zapis double.

**Zwraca:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```


Zwraca lub ustawia dolny margines (punkty) w TextFrame. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |
### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```


Prawda, jeśli tekst jest zawijany przy marginesach TextFrame. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public final void setWrapText(byte value)
```


Prawda, jeśli tekst jest zawijany przy marginesach TextFrame. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getAnchoringType() {#getAnchoringType--}
```
public final byte getAnchoringType()
```


Zwraca lub ustawia pionowy tekst kotwiczenia w TextFrame. Odczyt/zapis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Zwraca:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```


Zwraca lub ustawia pionowy tekst kotwiczenia w TextFrame. Odczyt/zapis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```


Jeśli NullableBool.True, tekst powinien być wyśrodkowany w poziomie w ramce. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```


Jeśli NullableBool.True, tekst powinien być wyśrodkowany w poziomie w ramce. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```


Określa orientację tekstu. Wynikowa wartość wizualnego obrotu tekstu podsumowana z tej właściwości i niestandardowego kąta w właściwości RotationAngle. Odczyt/zapis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Zwraca:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```


Określa orientację tekstu. Wynikowa wartość wizualnego obrotu tekstu podsumowana z tej właściwości i niestandardowego kąta w właściwości RotationAngle. Odczyt/zapis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```


Zwraca lub ustawia tryb dopasowania automatycznego tekstu. Odczyt/zapis [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code shows how to shrink text on overflow.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public final void setAutofitType(byte value)
```


Zwraca lub ustawia tryb dopasowania automatycznego tekstu. Odczyt/zapis [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code shows how to shrink text on overflow.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```


Zwraca lub ustawia liczbę kolumn w obszarze tekstu. Ta wartość musi być liczbą dodatnią. W przeciwnym razie wartość zostanie ustawiona na zero. Wartość 0 oznacza nieokreśloną wartość. Odczyt/zapis int.

--------------------

> ```
> The following sample code shows how to add column in Text frame inside a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public final void setColumnCount(int value)
```


Zwraca lub ustawia liczbę kolumn w obszarze tekstu. Ta wartość musi być liczbą dodatnią. W przeciwnym razie wartość zostanie ustawiona na zero. Wartość 0 oznacza nieokreśloną wartość. Odczyt/zapis int.

--------------------

> ```
> The following sample code shows how to add column in Text frame inside a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getColumnSpacing() {#getColumnSpacing--}
```
public final double getColumnSpacing()
```


Zwraca lub ustawia odstęp pomiędzy kolumnami tekstu w obszarze tekstu (w punktach). Powinno mieć zastosowanie tylko, gdy istnieje więcej niż 1 kolumna. Ta wartość musi być liczbą dodatnią. W przeciwnym razie wartość zostanie ustawiona na zero. Odczyt/zapis double.

**Zwraca:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```


Zwraca lub ustawia odstęp pomiędzy kolumnami tekstu w obszarze tekstu (w punktach). Powinno mieć zastosowanie tylko, gdy istnieje więcej niż 1 kolumna. Ta wartość musi być liczbą dodatnią. W przeciwnym razie wartość zostanie ustawiona na zero. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |
### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```


Określa niestandardowy obrót stosowany do tekstu w obrębie ramki ograniczającej. Jeśli nie jest określony, używany jest obrót powiązanej figury. Jeśli jest określony, jest stosowany niezależnie od figury. Oznacza to, że figura może mieć zastosowany obrót dodatkowo do obrotu samego tekstu. Wynikowa wartość wizualnego obrotu tekstu podsumowana z tej właściwości i zdefiniowanego typu pionowego w właściwości TextVerticalType. Odczyt/zapis float.

--------------------

> ```
> Rozważmy przypadek, w którym kształt ma zastosowany obrót o 90 stopni zgodnie z ruchem wskazówek zegara. 
>  Dodatkowo sam korpus tekstu ma zastosowany obrót o -90 stopni 
>  przeciwnie do ruchu wskazówek zegara. Następnie wynikowy kształt wydawałby się 
>  obrócony, ale tekst wewnątrz niego wydawałby się nieobrócony wcale.
```

**Zwraca:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```


Określa niestandardowy obrót stosowany do tekstu w obrębie ramki ograniczającej. Jeśli nie jest określony, używany jest obrót powiązanej figury. Jeśli jest określony, jest stosowany niezależnie od figury. Oznacza to, że figura może mieć zastosowany obrót dodatkowo do obrotu samego tekstu. Wynikowa wartość wizualnego obrotu tekstu podsumowana z tej właściwości i zdefiniowanego typu pionowego w właściwości TextVerticalType. Odczyt/zapis float.

--------------------

> ```
> Rozważmy przypadek, w którym kształt ma zastosowany obrót o 90 stopni zgodnie z ruchem wskazówek zegara. 
>  Dodatkowo sam korpus tekstu ma zastosowany obrót o -90 stopni 
>  przeciwnie do ruchu wskazówek zegara. Następnie wynikowy kształt wydawałby się 
>  obrócony, ale tekst w nim zawarty wydawałby się nieobrócony wcale.
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |
### getTransform() {#getTransform--}
```
public final byte getTransform()
```


Pobiera lub ustawia kształt zawijania tekstu. Odczyt/zapis [TextShapeType](../../com.aspose.slides/textshapetype).

**Zwraca:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```


Pobiera lub ustawia kształt zawijania tekstu. Odczyt/zapis [TextShapeType](../../com.aspose.slides/textshapetype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```


Pobiera lub ustawia utrzymanie płaskości tekstu nawet po zastosowaniu efektu obrotu 3D. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```


Pobiera lub ustawia utrzymanie płaskości tekstu nawet po zastosowaniu efektu obrotu 3D. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```


Pobiera efektywne dane formatowania ramki tekstowej z zastosowanym dziedziczeniem.

--------------------

> ```
> This example demonstrates getting some of effective text frame formatting properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextFrameFormatEffectiveData effectiveTextFrameFormat = shape.getTextFrame().getTextFrameFormat().getEffective();
>     
>      System.out.println("Anchoring type: " + effectiveTextFrameFormat.getAnchoringType());
>      System.out.println("Autofit type: " + effectiveTextFrameFormat.getAutofitType());
>      System.out.println("Text vertical type: " + effectiveTextFrameFormat.getTextVerticalType());
>      System.out.println("Margins");
>      System.out.println("   Left: " + effectiveTextFrameFormat.getMarginLeft());
>      System.out.println("   Top: " + effectiveTextFrameFormat.getMarginTop());
>      System.out.println("   Right: " + effectiveTextFrameFormat.getMarginRight());
>      System.out.println("   Bottom: " + effectiveTextFrameFormat.getMarginBottom());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).