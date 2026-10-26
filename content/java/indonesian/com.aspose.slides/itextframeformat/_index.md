---
title: ITextFrameFormat
second_title: Aspose.Slides for Java API Reference
description: Berisi properti pemformatan TextFrames.
type: docs
url: /id/com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

Berisi properti pemformatan TextFrame.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Mengembalikan gaya teks. |
| [getMarginLeft()](#getMarginLeft--) | Mengembalikan atau mengatur margin kiri (point) dalam TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Mengembalikan atau mengatur margin kiri (point) dalam TextFrame. |
| [getMarginRight()](#getMarginRight--) | Mengembalikan atau mengatur margin kanan (point) dalam TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Mengembalikan atau mengatur margin kanan (point) dalam TextFrame. |
| [getMarginTop()](#getMarginTop--) | Mengembalikan atau mengatur margin atas (point) dalam TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Mengembalikan atau mengatur margin atas (point) dalam TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Mengembalikan atau mengatur margin bawah (point) dalam TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Mengembalikan atau mengatur margin bawah (point) dalam TextFrame. |
| [getWrapText()](#getWrapText--) | Benar jika teks dibungkus pada margin TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | Benar jika teks dibungkus pada margin TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Mengembalikan atau mengatur teks jangkar vertikal dalam TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Mengembalikan atau mengatur teks jangkar vertikal dalam TextFrame. |
| [getCenterText()](#getCenterText--) | Jika NullableBool.True maka teks harus dipusatkan secara horizontal dalam kotak. |
| [setCenterText(byte value)](#setCenterText-byte-) | Jika NullableBool.True maka teks harus dipusatkan secara horizontal dalam kotak. |
| [getTextVerticalType()](#getTextVerticalType--) | Menentukan orientasi teks. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Menentukan orientasi teks. |
| [getAutofitType()](#getAutofitType--) | Mengembalikan atau mengatur mode autofit teks. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Mengembalikan atau mengatur mode autofit teks. |
| [getColumnCount()](#getColumnCount--) | Mengembalikan atau mengatur jumlah kolom di area teks. |
| [setColumnCount(int value)](#setColumnCount-int-) | Mengembalikan atau mengatur jumlah kolom di area teks. |
| [getColumnSpacing()](#getColumnSpacing--) | Mengembalikan atau mengatur spasi antar kolom teks di area teks (dalam point). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Mengembalikan atau mengatur spasi antar kolom teks di area teks (dalam point). |
| [getThreeDFormat()](#getThreeDFormat--) | Mengembalikan objek ThreeDFormat yang mewakili properti efek 3d untuk teks. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Mengembalikan atau mengatur agar teks tidak berada dalam adegan 3D sama sekali. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Mengembalikan atau mengatur agar teks tidak berada dalam adegan 3D sama sekali. |
| [getRotationAngle()](#getRotationAngle--) | Menentukan rotasi khusus yang diterapkan pada teks dalam kotak pembatas. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Menentukan rotasi khusus yang diterapkan pada teks dalam kotak pembatas. |
| [getTransform()](#getTransform--) | Mendapatkan atau mengatur bentuk pembungkus teks. |
| [setTransform(byte value)](#setTransform-byte-) | Mendapatkan atau mengatur bentuk pembungkus teks. |
| [getEffective()](#getEffective--) | Mendapatkan data pemformatan bingkai teks yang efektif dengan warisan yang diterapkan. |

### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```

Mengembalikan gaya teks. Baca-saja [ITextStyle](../../com.aspose.slides/itextstyle).

**Mengembalikan:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Mengembalikan atau mengatur margin kiri (point) dalam TextFrame. Baca/tulis double.

**Mengembalikan:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Mengembalikan atau mengatur margin kiri (point) dalam TextFrame. Baca/tulis double.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Mengembalikan atau mengatur margin kanan (point) dalam TextFrame. Baca/tulis double.

**Mengembalikan:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Mengembalikan atau mengatur margin kanan (point) dalam TextFrame. Baca/tulis double.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Mengembalikan atau mengatur margin atas (point) dalam TextFrame. Baca/tulis double.

**Mengembalikan:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Mengembalikan atau mengatur margin atas (point) dalam TextFrame. Baca/tulis double.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Mengembalikan atau mengatur margin bawah (point) dalam TextFrame. Baca/tulis double.

**Mengembalikan:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Mengembalikan atau mengatur margin bawah (point) dalam TextFrame. Baca/tulis double.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

Benar jika teks dibungkus pada margin TextFrame. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

Benar jika teks dibungkus pada margin TextFrame. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Mengembalikan atau mengatur teks jangkar vertikal dalam TextFrame. Baca/tulis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Mengembalikan:**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Mengembalikan atau mengatur teks jangkar vertikal dalam TextFrame. Baca/tulis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Jika NullableBool.True maka teks harus dipusatkan secara horizontal dalam kotak. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Jika NullableBool.True maka teks harus dipusatkan secara horizontal dalam kotak. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Menentukan orientasi teks. Nilai rotasi visual teks yang dirangkum dari properti ini dan tipe vertikal yang telah ditentukan dalam properti TextVerticalType. Baca/tulis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Mengembalikan:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Menentukan orientasi teks. Nilai rotasi visual teks yang dirangkum dari properti ini dan tipe vertikal yang telah ditentukan dalam properti TextVerticalType. Baca/tulis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Mengembalikan atau mengatur mode autofit teks. Baca/tulis [TextAutofitType](../../com.aspose.slides/textautofittype).

**Mengembalikan:**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Mengembalikan atau mengatur mode autofit teks. Baca/tulis [TextAutofitType](../../com.aspose.slides/textautofittype).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Mengembalikan atau mengatur jumlah kolom di area teks. Nilai ini harus berupa angka positif. Jika tidak, nilai akan diatur menjadi nol. Nilai 0 berarti nilai tak terdefinisi. Baca/tulis int.

**Mengembalikan:**
int

### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```

Mengembalikan atau mengatur jumlah kolom di area teks. Nilai ini harus berupa angka positif. Jika tidak, nilai akan diatur menjadi nol. Nilai 0 berarti nilai tak terdefinisi. Baca/tulis int.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```

Mengembalikan atau mengatur spasi antar kolom teks di area teks (dalam point). Ini hanya berlaku ketika lebih dari 1 kolom ada. Nilai ini harus berupa angka positif. Jika tidak, nilai akan diatur menjadi nol. Baca/tulis double.

**Mengembalikan:**
double

### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```

Mengembalikan atau mengatur spasi antar kolom teks di area teks (dalam point). Ini hanya berlaku ketika lebih dari 1 kolom ada. Nilai ini harus berupa angka positif. Jika tidak, nilai akan diatur menjadi nol. Baca/tulis double.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Mengembalikan objek ThreeDFormat yang mewakili properti efek 3d untuk teks. Baca-saja [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Atur transformasi teks
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // Atur Ekstrusi
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // Atur Kontur
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // Atur Kedalaman
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // Atur Material
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // Atur Pencahayaan
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // Atur tipe kamera
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getKeepTextFlat() {#getKeepTextFlat--}
```
public abstract boolean getKeepTextFlat()
```

Mengembalikan atau mengatur agar teks tidak berada dalam adegan 3D sama sekali. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```

Mengembalikan atau mengatur agar teks tidak berada dalam adegan 3D sama sekali. Baca/tulis boolean.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Menentukan rotasi khusus yang diterapkan pada teks dalam kotak pembatas. Jika tidak ditentukan, rotasi bentuk yang menyertainya digunakan. Jika ditentukan, maka ini diterapkan secara independen dari bentuk. Artinya bentuk dapat memiliki rotasi yang diterapkan selain teks itu sendiri yang memiliki rotasi yang diterapkan padanya. Nilai hasil rotasi visual teks yang dirangkum dari properti ini dan tipe vertikal yang telah ditentukan dalam properti TextVerticalType. Baca/tulis float.

--------------------

> ```
> Pertimbangkan kasus di mana sebuah bentuk memiliki rotasi 90 derajat searah jarum jam yang diterapkan padanya. 
>  Selain itu, badan teks itu sendiri memiliki rotasi -90 derajat berlawanan arah jarum jam yang diterapkan padanya. Maka bentuk yang dihasilkan akan tampak
>  terrotasi, namun teks di dalamnya akan tampak seolah-olah tidak pernah berotasi sama sekali.
> ```

**Mengembalikan:**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Menentukan rotasi khusus yang diterapkan pada teks dalam kotak pembatas. Jika tidak ditentukan, rotasi bentuk yang menyertainya digunakan. Jika ditentukan, maka ini diterapkan secara independen dari bentuk. Artinya bentuk dapat memiliki rotasi yang diterapkan selain teks itu sendiri yang memiliki rotasi yang diterapkan padanya. Nilai hasil rotasi visual teks yang dirangkum dari properti ini dan tipe vertikal yang telah ditentukan dalam properti TextVerticalType. Baca/tulis float.

--------------------

> ```
> Pertimbangkan kasus di mana sebuah bentuk memiliki rotasi 90 derajat searah jarum jam yang diterapkan padanya. 
>  Selain itu, badan teks itu sendiri memiliki rotasi -90 derajat 
>  berlawanan arah jarum jam yang diterapkan padanya. Maka bentuk yang dihasilkan akan tampak 
>  terrotasi, namun teks di dalamnya akan tampak seolah-olah tidak pernah berotasi sama sekali. 
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```

Mendapatkan atau mengatur bentuk pembungkus teks. Baca/tulis [TextShapeType](../../com.aspose.slides/textshapetype).

**Mengembalikan:**
byte

### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```

Mendapatkan atau mengatur bentuk pembungkus teks. Baca/tulis [TextShapeType](../../com.aspose.slides/textshapetype).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
```

Mendapatkan data pemformatan bingkai teks yang efektif dengan warisan yang diterapkan.

**Mengembalikan:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).