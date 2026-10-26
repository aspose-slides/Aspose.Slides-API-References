---
title: Control
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: ActiveX 컨트롤을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/control/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IControl](../../com.aspose.slides/icontrol)
```
public class Control extends DomObject<ControlCollection> implements IControl
```

ActiveX 컨트롤을 나타냅니다.

## Methods

| Method | Description |
| --- | --- |
| [getPersistence()](#getPersistence--) | ActiveX 컨트롤의 속성을 저장하는 데 사용되는 메서드를 가져옵니다. |
| [getName()](#getName--) | 이 컨트롤의 이름을 가져오거나 설정합니다. |
| [setName(String value)](#setName-java.lang.String-) | 이 컨트롤의 이름을 가져오거나 설정합니다. |
| [getClassId()](#getClassId--) | 이 컨트롤의 클래스 ID를 가져옵니다. |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | 이 컨트롤의 클래스 ID를 가져옵니다. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Control 이미지 채우기 속성 객체를 반환합니다. |
| [getFrame()](#getFrame--) | 컨트롤의 프레임을 반환하거나 설정합니다. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | 컨트롤의 프레임을 반환하거나 설정합니다. |
| [getProperties()](#getProperties--) | ActiveX 속성 컬렉션을 반환합니다. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | PersistStream, PersistStreamInit 또는 PersistStorage 중 하나인 지속 방법을 사용할 때 ActiveX 컨트롤의 지속성을 지정합니다. |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |

### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```

ActiveX 컨트롤의 속성을 저장하는 데 사용되는 메서드를 가져옵니다. 읽기 전용 [PersistenceType](../../com.aspose.slides/persistencetype).

--------------------

> ```
> Next example shows the using Persistence property for checking if properties of ActiveX object may be changed as XML based ActiveX properties:
>  
>  if (control.getPersistence() == PersistenceType.PersistPropertyBag)
>  {
>      control.getProperties().set_Item("Value", value);
>  }
>  else
>  {
>      YourMethodHere(control.getActiveXControlBinary()); //바이너리 파일에 저장된 ActiveX 속성을 관리하기 위한 자체 메서드를 사용하세요
>  }
> ```


**Returns:**
int

### getName() {#getName--}
```
public final String getName()
```

이 컨트롤의 이름을 가져오거나 설정합니다. 읽기/쓰기 String.

**Returns:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

이 컨트롤의 이름을 가져오거나 설정합니다. 읽기/쓰기 String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```

이 컨트롤의 클래스 ID를 가져옵니다. 읽기 전용 java.util.UUID.

**Returns:**
java.util.UUID

### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```

이 컨트롤의 클래스 ID를 가져옵니다. 읽기 전용 java.util.UUID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Control 이미지 채우기 속성 객체를 반환합니다. 읽기 전용 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Returns:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

컨트롤의 프레임을 반환하거나 설정합니다. 읽기/쓰기 [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Returns:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

컨트롤의 프레임을 반환하거나 설정합니다. 읽기/쓰기 [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```

ActiveX 속성 컬렉션을 반환합니다. 읽기 전용 [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

--------------------

참고: Aspose.Slides는 XML 기반 ActiveX 속성만 지원합니다. 속성이 바이너리 형식으로 저장된 경우, 이 속성은 null을 반환합니다.

**Returns:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)

### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```

PersistStream, PersistStreamInit 또는 PersistStorage 중 하나인 지속 방법을 사용할 때 ActiveX 컨트롤의 지속성을 지정합니다.

--------------------

> ```
> Next example shows the using ActiveXControlBinary property for changing ActiveX properties:
>  
>  if (control.getPersistence() == PersistenceType.PersistPropertyBag)
>  {
>      control.getProperties().set_Item("Value", value);
>  }
>  else
>  {
>      YourMethodHere(control.getActiveXControlBinary()); //바이너리 파일에 저장된 ActiveX 속성을 관리하기 위해 자체 메서드를 사용하세요
>  }
> ```


**Returns:**
byte[]

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

기본 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)