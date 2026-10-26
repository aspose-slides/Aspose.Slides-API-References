---
title: ISmartArtNodeCollection
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: SmartArt 노드 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ismartartnodecollection/
---
**구현된 모든 인터페이스:**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

SmartArt 노드의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 인덱스로 노드를 반환합니다. |
| [addNode()](#addNode--) | 새 노드 또는 하위 노드를 추가합니다. |
| [removeNode(int index)](#removeNode-int-) | 인덱스로 노드 또는 하위 노드를 제거합니다. |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | 노드 또는 하위 노드를 제거합니다. |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | 노드 컬렉션에서 선택한 위치에 새 노드를 추가합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```

인덱스로 노드를 반환합니다. 읽기 전용 [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 요소의 0 기반 인덱스. |

**반환값:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)
### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```

새 노드 또는 하위 노드를 추가합니다.

**반환값:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - 추가된 노드
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```

인덱스로 노드 또는 하위 노드를 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 노드의 0 기반 인덱스. |
### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```

노드 또는 하위 노드를 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | 제거할 노드. |
### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```

노드 컬렉션에서 선택한 위치에 새 노드를 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | int | 노드의 0 기반 위치. |

**반환값:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - 추가된 노드