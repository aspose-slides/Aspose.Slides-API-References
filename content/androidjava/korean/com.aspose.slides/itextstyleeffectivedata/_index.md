---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: 효과적인 텍스트 스타일 속성을 포함하는 불변 객체입니다.
type: docs
url: /ko/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

효과적인 텍스트 스타일 속성을 포함하는 불변 객체입니다.

--------------------

이 인터페이스는 [ITextStyle](../../com.aspose.slides/itextstyle) 인터페이스와 함께 사용되어 상속이 적용된 효과적인 서식 값을 반환합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | 효과적인 스타일의 레벨을 반환합니다. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | 효과적인 기본 단락 속성을 반환합니다. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```

효과적인 스타일의 레벨을 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 레벨의 0부터 시작하는 인덱스입니다. 0..8 범위에 있어야 합니다. |

**반환값:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - 레벨 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)의 효과적인 서식
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```

효과적인 기본 단락 속성을 반환합니다. 읽기 전용 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**반환값:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)