---
title: ICellCollection
second_title: Java API 참조용 Aspose.Slides for Android
description: 셀 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/icellcollection/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

셀 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 셀을 해당 위치에서 반환합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```

셀을 해당 위치에서 반환합니다. 읽기 전용 [ICell](../../com.aspose.slides/icell).

--------------------

셀을 병합한 경우 여러 인덱스에 대해 하나의 CellEx 객체를 반환할 수 있습니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[ICell](../../com.aspose.slides/icell)