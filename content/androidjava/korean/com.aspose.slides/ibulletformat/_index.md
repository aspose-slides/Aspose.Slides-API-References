---
title: IBulletFormat
second_title: Aspose.Slides for Android via Java API Reference
description: 문단 글머리표 서식 속성을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

문단 글머리표 서식 속성을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getType()](#getType--) | 상속 없이 문단의 글머리표 유형을 반환하거나 설정합니다. |
| [setType(byte value)](#setType-byte-) | 상속 없이 문단의 글머리표 유형을 반환하거나 설정합니다. |
| [getChar()](#getChar--) | 상속 없이 문단의 글머리표 문자를 반환하거나 설정합니다. |
| [setChar(char value)](#setChar-char-) | 상속 없이 문단의 글머리표 문자를 반환하거나 설정합니다. |
| [getFont()](#getFont--) | 상속 없이 문단의 글머리표 글꼴을 반환하거나 설정합니다. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | 상속 없이 문단의 글머리표 글꼴을 반환하거나 설정합니다. |
| [getHeight()](#getHeight--) | 상속 없이 문단의 글머리표 높이를 반환하거나 설정합니다. |
| [setHeight(float value)](#setHeight-float-) | 상속 없이 문단의 글머리표 높이를 반환하거나 설정합니다. |
| [getColor()](#getColor--) | 상속 없이 문단의 글머리표 색상 형식을 반환합니다. |
| [getPicture()](#getPicture--) | 상속 없이 문단에서 글머리표로 사용되는 그림을 반환합니다. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | 상속 없이 번호 매기기 글머리표 그룹에 사용되는 첫 번째 번호를 반환하거나 설정합니다. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | 상속 없이 번호 매기기 글머리표 그룹에 사용되는 첫 번째 번호를 반환하거나 설정합니다. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | 상속 없이 번호 매기기 글머리표의 스타일을 반환하거나 설정합니다. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | 상속 없이 번호 매기기 글머리표의 스타일을 반환하거나 설정합니다. |
| [isBulletHardColor()](#isBulletHardColor--) | 글머리표가 자체 색상을 가지고 있는지 또는 문단의 첫 번째 부분에서 색상을 상속받는지 확인합니다. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | 글머리표가 자체 색상을 가지고 있는지 또는 문단의 첫 번째 부분에서 색상을 상속받는지 확인합니다. |
| [isBulletHardFont()](#isBulletHardFont--) | 글머리표가 자체 글꼴을 가지고 있는지 또는 문단의 첫 번째 부분에서 글꼴을 상속받는지 확인합니다. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | 글머리표가 자체 글꼴을 가지고 있는지 또는 문단의 첫 번째 부분에서 글꼴을 상속받는지 확인합니다. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | 글머리표가 활성화된 경우 효과적인 문단 Indent와 MarginLeft에 대해 기본 비영(非零) 이동을 설정합니다(PowerPoint가 문단 글머리표/번호 매기기를 활성화할 때와 동일). |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 글머리표 서식 데이터를 가져옵니다. |
### getType() {#getType--}
```
public abstract byte getType()
```

상속 없이 문단의 글머리표 유형을 반환하거나 설정합니다. 읽기/쓰기 [BulletType](../../com.aspose.slides/bullettype).

**반환:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

상속 없이 문단의 글머리표 유형을 반환하거나 설정합니다. 읽기/쓰기 [BulletType](../../com.aspose.slides/bullettype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getChar() {#getChar--}
```
public abstract char getChar()
```

상속 없이 문단의 글머리표 문자를 반환하거나 설정합니다. 읽기/쓰기 char.

**반환:**
char
### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```

상속 없이 문단의 글머리표 문자를 반환하거나 설정합니다. 읽기/쓰기 char.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | char |  |
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

상속 없이 문단의 글머리표 글꼴을 반환하거나 설정합니다. 읽기/쓰기 [IFontData](../../com.aspose.slides/ifontdata).

**반환:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```

상속 없이 문단의 글머리표 글꼴을 반환하거나 설정합니다. 읽기/쓰기 [IFontData](../../com.aspose.slides/ifontdata).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

상속 없이 문단의 글머리표 높이를 반환하거나 설정합니다. 값 Float.NaN은 글머리표가 문단의 첫 번째 부분에서 높이를 상속받음음을 나타냅니다. 읽기/쓰기 float.

**반환:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

상속 없이 문단의 글머리표 높이를 반환하거나 설정합니다. 값 Float.NaN은 글머리표가 문단의 첫 번째 부분에서 높이를 상속받음음을 나타냅니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

상속 없이 문단의 글머리표 색상 형식을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

상속 없이 문단에서 글머리표로 사용되는 그림을 반환합니다. 읽기 전용 [ISlidesPicture](../../com.aspose.slides/islidespicture).

**반환:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

상속 없이 번호 매기기 글머리표 그룹에 사용되는 첫 번째 번호를 반환하거나 설정합니다. 읽기/쓰기 short.

**반환:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```

상속 없이 번호 매기기 글머리표 그룹에 사용되는 첫 번째 번호를 반환하거나 설정합니다. 읽기/쓰기 short.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | short |  |
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

상속 없이 번호 매기기 글머리표의 스타일을 반환하거나 설정합니다. 읽기/쓰기 [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**반환:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```

상속 없이 번호 매기기 글머리표의 스타일을 반환하거나 설정합니다. 읽기/쓰기 [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```

글머리표가 자체 색상을 가지고 있는지 또는 문단의 첫 번째 부분에서 색상을 상속받는지 결정합니다. **NullableBool#True**이면 자체 색상이 있고 **NullableBool#False**이면 문단 첫 번째 부분에서 색상을 상속받습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```

글머리표가 자체 색상을 가지고 있는지 또는 문단의 첫 번째 부분에서 색상을 상속받는지 결정합니다. **NullableBool#True**이면 자체 색상이 있고 **NullableBool#False**이면 문단 첫 번째 부분에서 색상을 상속받습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```

글머리표가 자체 글꼴을 가지고 있는지 또는 문단의 첫 번째 부분에서 글꼴을 상속받는지 결정합니다. **NullableBool#True**이면 자체 글꼴이 있고 **NullableBool#False**이면 문단 첫 번째 부분에서 글꼴을 상속받습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```

글머리표가 자체 글꼴을 가지고 있는지 또는 문단의 첫 번째 부분에서 글꼴을 상속받는지 결정합니다. **NullableBool#True**이면 자체 글꼴이 있고 **NullableBool#False**이면 문단 첫 번째 부분에서 글꼴을 상속받습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```

글머리표가 활성화된 경우 효과적인 문단 Indent와 MarginLeft에 대해 기본 비영(非零) 이동을 설정합니다(PowerPoint가 문단 글머리표/번호 매기기를 활성화할 때와 동일). 글머리표가 비활성화된 경우에는 문단 Indent와 MarginLeft를 재설정합니다(PowerPoint가 문단 글머리표/번호 매기기를 비활성화할 때와 동일). Indent 이동은 현재 글머리표 컨텍스트—IBulletFormat.Type, .NumberedBulletStyle 및 첫 번째 부분의 FontHeight—를 기준으로 적용됩니다. 비영(非零) Indent 이동은 현재 문단의 효과적인 Indent와 MarginLeft에 적용되어 결과 값이 로컬 값이 됩니다.
### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```

상속이 적용된 효과적인 글머리표 서식 데이터를 가져옵니다.

--------------------

> ```
> This example demonstrates getting some effective bullet format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IBulletFormatEffectiveData effectiveBulletFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getBullet().getEffective();
>      System.out.println("Bullet type: " + effectiveBulletFormat.getType());
>      if (effectiveBulletFormat.getType() == BulletType.Numbered)
>      {
>          System.out.println("Numbered style: " + effectiveBulletFormat.getNumberedBulletStyle());
>          System.out.println("Starting number: " + effectiveBulletFormat.getNumberedBulletStartWith());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - A [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).