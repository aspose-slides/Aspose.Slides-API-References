---
title: IControlCollection
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: ActiveX 컨트롤의 컬렉션입니다.
type: docs
url: /ko/com.aspose.slides/icontrolcollection/
---
**구현된 모든 인터페이스:**  
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

ActiveX 컨트롤의 컬렉션입니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | 컬렉션에서 ActiveX 컨트롤을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 위치에 저장된 ActiveX 컨트롤을 컬렉션에서 제거합니다. |
| [clear()](#clear--) | 컬렉션의 모든 컨트롤을 제거합니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 위치에 있는 컨트롤을 반환합니다. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | 새 컨트롤을 생성하고 컬렉션에 추가합니다. |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```

컬렉션에서 ActiveX 컨트롤을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | 제거할 컨트롤. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

지정된 위치에 저장된 ActiveX 컨트롤을 컬렉션에서 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 제거할 컨트롤의 인덱스. |

### clear() {#clear--}
```
public abstract void clear()
```

컬렉션에서 모든 컨트롤을 제거합니다.

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```

지정된 위치에 있는 컨트롤을 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 컨트롤의 인덱스. |

**반환값:**
[IControl](../../com.aspose.slides/icontrol)
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```

컬렉션에 새 컨트롤을 생성하고 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| controlType | int | 추가할 컨트롤의 유형. |
| x | float | 쉐이프 프레임의 왼쪽 면에 대한 X 좌표. |
| y | float | 쉐이프 프레임의 위쪽 면에 대한 Y 좌표. |
| width | float | 쉐이프 프레임의 너비. |
| height | float | 쉐이프 프레임의 높이. |

**반환값:**
[IControl](../../com.aspose.slides/icontrol) - 생성된 컨트롤 [IControl](../../com.aspose.slides/icontrol).