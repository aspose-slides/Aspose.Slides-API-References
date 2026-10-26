---
title: Control
second_title: Aspose.Slides for Java API 참조
description: ActiveX 컨트롤을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/control/
---
**상속:**  
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**  
[com.aspose.slides.IControl](../../com.aspose.slides/icontrol)  
```
public class Control extends DomObject<ControlCollection> implements IControl
```

ActiveX 컨트롤을 나타냅니다.  
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPersistence()](#getPersistence--) | ActiveX 컨트롤의 속성을 저장하는 데 사용되는 메서드를 가져옵니다. |
| [getName()](#getName--) | 이 컨트롤의 이름을 가져오거나 설정합니다. |
| [setName(String value)](#setName-java.lang.String-) | 이 컨트롤의 이름을 가져오거나 설정합니다. |
| [getClassId()](#getClassId--) | 이 컨트롤의 클래스 ID를 가져옵니다. |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | 이 컨트롤의 클래스 ID를 가져옵니다. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Control 이미지 채우기 속성 객체를 반환합니다. |
| [getFrame()](#getFrame--) | control의 프레임을 반환하거나 설정합니다. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | control의 프레임을 반환하거나 설정합니다. |
| [getProperties()](#getProperties--) | ActiveX 속성 컬렉션을 반환합니다. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | PersistStream, PersistStreamInit 또는 PersistStorage 중 하나를 사용하여 ActiveX 컨트롤의 지속성을 지정합니다. |
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
>      YourMethodHere(control.getActiveXControlBinary()); //ActiveX 속성을 이진 파일에 저장된 상태로 관리하기 위한 자체 메서드를 사용하세요
>  }
> ```


**반환값:**  
int

### getName() {#getName--}
```
public final String getName()
```

이 컨트롤의 이름을 가져오거나 설정합니다. 읽기/쓰기 String.

**반환값:**  
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

이 컨트롤의 이름을 가져오거나 설정합니다. 읽기/쓰기 String.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```

이 컨트롤의 클래스 ID를 가져옵니다. 읽기 전용 java.util.UUID.

**반환값:**  
java.util.UUID

### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```

이 컨트롤의 클래스 ID를 가져옵니다. 읽기 전용 java.util.UUID.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Control 이미지 채우기 속성 객체를 반환합니다. 읽기 전용 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**반환값:**  
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

control의 프레임을 반환하거나 설정합니다. 읽기/쓰기 [IShapeFrame](../../com.aspose.slides/ishapeframe).

**반환값:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

control의 프레임을 반환하거나 설정합니다. 읽기/쓰기 [IShapeFrame](../../com.aspose.slides/ishapeframe).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```

ActiveX 속성 컬렉션을 반환합니다. 읽기 전용 [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

--------------------

참고: Aspose.Slides는 XML 기반 ActiveX 속성만 지원합니다. 속성이 바이너리 형식으로 저장된 경우, 이 속성은 null을 반환합니다.

**반환값:**  
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)

### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```

PersistStream, PersistStreamInit 또는 PersistStorage 중 하나를 사용하여 ActiveX 컨트롤의 지속성을 지정합니다.

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
>      YourMethodHere(control.getActiveXControlBinary()); //ActiveX 속성을 이진 파일에 저장된 상태로 관리하기 위한 자체 메서드를 사용하세요
>  }
> ```


**반환값:**  
byte[]

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

기본 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../../com.aspose.slides/ibaseslide).

**반환값:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../com.aspose.slides/ipresentation).

**반환값:**  
[IPresentation](../../com.aspose.slides/ipresentation)