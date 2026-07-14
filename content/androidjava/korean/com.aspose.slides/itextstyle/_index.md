---
title: ITextStyle
second_title: Aspose.Slides for Android via Java API Reference
description: Text style formatting properties.
type: docs
url: /ko/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

텍스트 스타일 서식 속성.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | 스타일 레벨이 존재하면 반환하고, 없으면 null을 반환합니다. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | 기본 단락 속성. |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 텍스트 스타일 서식 데이터를 가져옵니다. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

스타일 레벨이 존재하면 반환하고, 없으면 null을 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 레벨의 0 기반 인덱스. 0..8 구간에 있어야 합니다. |

**반환값:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - 레벨 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)의 서식.
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```

기본 단락 속성. 읽기 전용 [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**반환값:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

상속이 적용된 효과적인 텍스트 스타일 서식 데이터를 가져옵니다.

**반환값:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - A [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).