---
title: IControl
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: ActiveX 컨트롤을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/icontrol/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

ActiveX 컨트롤을 나타냅니다.
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | 이 컨트롤의 이름을 반환합니다. |
| [setName(String value)](#setName-java.lang.String-) | 이 컨트롤의 이름을 반환합니다. |
| [getClassId()](#getClassId--) | 이 컨트롤의 클래스 ID를 가져옵니다. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | ControlEx 이미지 채우기 속성 객체를 반환합니다. |
| [getFrame()](#getFrame--) | 컨트롤의 프레임을 반환하거나 설정합니다. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | 컨트롤의 프레임을 반환하거나 설정합니다. |
| [getProperties()](#getProperties--) | ActiveX 속성 컬렉션을 반환합니다. |
| [getPersistence()](#getPersistence--) | ActiveX 컨트롤의 속성을 저장하는 데 사용되는 메서드를 가져옵니다. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | 지속 방법이 PersistStream, PersistStreamInit 또는 PersistStorage인 경우 ActiveX 컨트롤의 지속성을 지정합니다. |
### getName() {#getName--}
```
public abstract String getName()
```

이 컨트롤의 이름을 반환합니다. 읽기/쓰기 String.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

이 컨트롤의 이름을 반환합니다. 읽기/쓰기 String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```

이 컨트롤의 클래스 ID를 가져옵니다. 읽기 전용 java.util.UUID.

**Returns:**
java.util.UUID
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

ControlEx 이미지 채우기 속성 객체를 반환합니다. 읽기 전용 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Returns:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

컨트롤의 프레임을 반환하거나 설정합니다. 읽기/쓰기 [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Returns:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

컨트롤의 프레임을 반환하거나 설정합니다. 읽기/쓰기 [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |
### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```

ActiveX 속성 컬렉션을 반환합니다. 읽기 전용 [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

**Returns:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```

ActiveX 컨트롤의 속성을 저장하는 데 사용되는 메서드를 가져옵니다. 읽기 전용 [PersistenceType](../../com.aspose.slides/persistencetype).

**Returns:**
int
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```

지속 방법이 PersistStream, PersistStreamInit 또는 PersistStorage인 경우 ActiveX 컨트롤의 지속성을 지정합니다.

**Returns:**
byte[]