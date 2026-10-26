---
title: ITextAnimationCollection
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 텍스트 애니메이션 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/itextanimationcollection/
---
**구현된 모든 인터페이스:**
com.aspose.slides.IGenericCollection
```
public interface ITextAnimationCollection extends IGenericCollection<ITextAnimation>
```

텍스트 애니메이션 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 인덱스로 요소를 반환합니다. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | 모든 요소를 반환합니다 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITextAnimation get_Item(int index)
```


인덱스로 요소를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public abstract ITextAnimation[] get_Item(IShape shape)
```


모든 요소를 반환합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) 요소. |

**반환값:**
com.aspose.slides.ITextAnimation[] - [ITextAnimation](../../com.aspose.slides/itextanimation) 배열