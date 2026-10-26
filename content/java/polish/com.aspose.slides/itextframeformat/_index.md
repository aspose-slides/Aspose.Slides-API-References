---
title: ITextFrameFormat
second_title: Aspose.Slides for Java API Reference
description: Zawiera właściwości formatowania TextFrames.
type: docs
url: /pl/com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

Zawiera właściwości formatowania TextFrame.

## Metody

| Metoda | Opis |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Zwraca styl tekstu. |
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
| [getAnchoringType()](#getAnchoringType--) | Zwraca lub ustawia pionowy punkt kotwiczenia tekstu w TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Zwraca lub ustawia pionowy punkt kotwiczenia tekstu w TextFrame. |
| [getCenterText()](#getCenterText--) | Jeśli NullableBool.True, tekst powinien być wyśrodkowany w poziomie w ramce. |
| [setCenterText(byte value)](#setCenterText-byte-) | Jeśli NullableBool.True, tekst powinien być wyśrodkowany w poziomie w ramce. |
| [getTextVerticalType()](#getTextVerticalType--) | Określa orientację tekstu. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Określa orientację tekstu. |
| [getAutofitType()](#getAutofitType--) | Zwraca lub ustawia tryb dopasowania automatycznego tekstu. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Zwraca lub ustawia tryb dopasowania automatycznego tekstu. |
| [getColumnCount()](#getColumnCount--) | Zwraca lub ustawia liczbę kolumn w obszarze tekstu. |
| [setColumnCount(int value)](#setColumnCount-int-) | Zwraca lub ustawia liczbę kolumn w obszarze tekstu. |
| [getColumnSpacing()](#getColumnSpacing--) | Zwraca lub ustawia odstęp między kolumnami tekstu w obszarze tekstu (w punktach). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Zwraca lub ustawia odstęp między kolumnami tekstu w obszarze tekstu (w punktach). |
| [getThreeDFormat()](#getThreeDFormat--) | Zwraca obiekt ThreeDFormat, który reprezentuje właściwości efektu 3D dla tekstu. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Zwraca lub ustawia utrzymanie tekstu całkowicie poza sceną 3D. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Zwraca lub ustawia utrzymanie tekstu całkowicie poza sceną 3D. |
| [getRotationAngle()](#getRotationAngle--) | Określa niestandardowy obrót stosowany do tekstu w obrębie ramki ograniczającej. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Określa niestandardowy obrót stosowany do tekstu w obrębie ramki ograniczającej. |
| [getTransform()](#getTransform--) | Zwraca lub ustawia kształt zawijania tekstu. |
| [setTransform(byte value)](#setTransform-byte-) | Zwraca lub ustawia kształt zawijania tekstu. |
| [getEffective()](#getEffective--) | Zwraca skuteczne dane formatowania ramki tekstu z zastosowaną dziedzicznością. |

### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```

Zwraca styl tekstu. Tylko do odczytu [ITextStyle](../../com.aspose.slides/itextstyle).

**Zwraca:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Zwraca lub ustawia lewy margines (punkty) w TextFrame. Odczyt/zapis double.

**Zwraca:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Zwraca lub ustawia lewy margines (punkty) w TextFrame. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Zwraca lub ustawia prawy margines (punkty) w TextFrame. Odczyt/zapis double.

**Zwraca:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Zwraca lub ustawia prawy margines (punkty) w TextFrame. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Zwraca lub ustawia górny margines (punkty) w TextFrame. Odczyt/zapis double.

**Zwraca:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Zwraca lub ustawia górny margines (punkty) w TextFrame. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Zwraca lub ustawia dolny margines (punkty) w TextFrame. Odczyt/zapis double.

**Zwraca:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Zwraca lub ustawia dolny margines (punkty) w TextFrame. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

Prawda, jeśli tekst jest zawijany przy marginesach TextFrame. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

Prawda, jeśli tekst jest zawijany przy marginesach TextFrame. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Zwraca lub ustawia pionowy punkt kotwiczenia tekstu w TextFrame. Odczyt/zapis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Zwraca:**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Zwraca lub ustawia pionowy punkt kotwiczenia tekstu w TextFrame. Odczyt/zapis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Jeśli NullableBool.True, tekst powinien być wyśrodkowany w poziomie w ramce. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Jeśli NullableBool.True, tekst powinien być wyśrodkowany w poziomie w ramce. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Określa orientację tekstu. Wynikowa wartość wizualnego obrotu tekstu podsumowana z tej właściwości i niestandardowego kąta w właściwości RotationAngle. Odczyt/zapis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Zwraca:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Określa orientację tekstu. Wynikowa wartość wizualnego obrotu tekstu podsumowana z tej właściwości i niestandardowego kąta w właściwości RotationAngle. Odczyt/zapis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Zwraca lub ustawia tryb dopasowania automatycznego tekstu. Odczyt/zapis [TextAutofitType](../../com.aspose.slides/textautofittype).

**Zwraca:**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Zwraca lub ustawia tryb dopasowania automatycznego tekstu. Odczyt/zapis [TextAutofitType](../../com.aspose.slides/textautofittype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Zwraca lub ustawia liczbę kolumn w obszarze tekstu. Wartość musi być dodatnia, w przeciwnym razie zostanie ustawiona na zero. Wartość 0 oznacza nieokreśloną wartość. Odczyt/zapis int.

**Zwraca:**
int

### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```

Zwraca lub ustawia liczbę kolumn w obszarze tekstu. Wartość musi być dodatnia, w przeciwnym razie zostanie ustawiona na zero. Wartość 0 oznacza nieokreśloną wartość. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```

Zwraca lub ustawia odstęp między kolumnami tekstu w obszarze tekstu (w punktach). Ma zastosowanie tylko, gdy istnieje więcej niż 1 kolumna. Wartość musi być dodatnia, w przeciwnym razie zostanie ustawiona na zero. Odczyt/zapis double.

**Zwraca:**
double

### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```

Zwraca lub ustawia odstęp między kolumnami tekstu w obszarze tekstu (w punktach). Ma zastosowanie tylko, gdy istnieje więcej niż 1 kolumna. Wartość musi być dodatnia, w przeciwnym razie zostanie ustawiona na zero. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Zwraca obiekt ThreeDFormat, który reprezentuje właściwości efektu 3D dla tekstu. Tylko do odczytu [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Ustaw transformację tekstu
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // Ustaw ekstruzję
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // Ustaw obrys
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

### getKeepTextFlat() {#getKeepTextFlat--}
```
public abstract boolean getKeepTextFlat()
```

Zwraca lub ustawia utrzymanie tekstu całkowicie poza sceną 3D. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```

Zwraca lub ustawia utrzymanie tekstu całkowicie poza sceną 3D. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Określa niestandardowy obrót stosowany do tekstu w obrębie ramki ograniczającej. Jeśli nie jest określony, używany jest obrót towarzyszącego kształtu. Jeśli jest określony, jest stosowany niezależnie od kształtu. Oznacza to, że kształt może mieć obrót dodatkowy do obrotu samego tekstu. Wynikowa wartość wizualnego obrotu tekstu podsumowana z tej właściwości i predefiniowanego typu pionowego w właściwości TextVerticalType. Odczyt/zapis float.

--------------------

> ```
> Rozważmy przypadek, w którym kształt ma zastosowaną rotację o 90 stopni zgodnie z ruchem wskazówek zegara. 
>  Dodatkowo sam korpus tekstu ma zastosowaną rotację o -90 stopni 
>  przeciwnie do ruchu wskazówek zegara. Wtedy powstały kształt wydaje się
>  być obrócony, ale tekst w jego wnętrzu wydaje się, jakby wcale nie został obrócony.
```

**Zwraca:**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Określa niestandardowy obrót stosowany do tekstu w obrębie ramki ograniczającej. Jeśli nie jest określony, używany jest obrót towarzyszącego kształtu. Jeśli jest określony, jest stosowany niezależnie od kształtu. Oznacza to, że kształt może mieć obrót dodatkowy do obrotu samego tekstu. Wynikowa wartość wizualnego obrotu tekstu podsumowana z tej właściwości i predefiniowanego typu pionowego w właściwości TextVerticalType. Odczyt/zapis float.

--------------------

> ```
> Rozważmy przypadek, w którym kształt ma zastosowaną rotację o 90 stopni zgodnie z ruchem wskazówek zegara. 
>  Dodatkowo sam korpus tekstu ma zastosowaną rotację o -90 stopni przeciwnie do ruchu wskazówek zegara. 
>  Wtedy powstały kształt wydaje się być obrócony, ale tekst w jego wnętrzu wydaje się, jakby wcale nie został obrócony. 
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```

Zwraca lub ustawia kształt zawijania tekstu. Odczyt/zapis [TextShapeType](../../com.aspose.slides/textshapetype).

**Zwraca:**
byte

### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```

Zwraca lub ustawia kształt zawijania tekstu. Odczyt/zapis [TextShapeType](../../com.aspose.slides/textshapetype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
```

Zwraca skuteczne dane formatowania ramki tekstu z zastosowaną dziedzicznością.

**Zwraca:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).