---
title: PresentationInfo
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 프레젠테이션 파일에 대한 정보
type: docs
url: /ko/com.aspose.slides/presentationinfo/
---
**Inheritance:**  
상속:

**All Implemented Interfaces:**  
구현된 모든 인터페이스:
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)
```
public final class PresentationInfo implements IPresentationInfo
```

프레젠테이션 파일에 대한 정보
## 메서드

| Method | Description |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | 바인드된 프레젠테이션이 암호화된 경우 True를 반환하고, 그렇지 않으면 False를 반환합니다. |
| [isPasswordProtected()](#isPasswordProtected--) | 바인드된 프레젠테이션이 열기 비밀번호로 보호되는지 여부를 나타내는 값을 반환합니다. |
| [isWriteProtected()](#isWriteProtected--) | 바인드된 프레젠테이션이 쓰기 보호되는지 여부를 나타내는 값을 반환합니다. |
| [getLoadFormat()](#getLoadFormat--) | 바인드된 프레젠테이션의 형식을 반환합니다. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | 열기 비밀번호로 보호된 프레젠테이션에 대해 비밀번호가 올바른지 확인합니다. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | 쓰기 보호된 프레젠테이션에 대해 수정 비밀번호가 올바른지 확인합니다. |
| [readDocumentProperties()](#readDocumentProperties--) | 바인드된 프레젠테이션의 문서 속성을 가져옵니다. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | 바인드된 프레젠테이션의 속성을 업데이트합니다. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | 바인드된 프레젠테이션을 스트림에 씁니다. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | 바인드된 프레젠테이션을 파일에 씁니다. |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

바인드된 프레젠테이션이 암호화된 경우 True를 반환하고, 그렇지 않으면 False를 반환합니다. 읽기 전용 boolean.

**Returns:**  
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

바인드된 프레젠테이션이 열기 비밀번호로 보호되는지 여부를 나타내는 값을 반환합니다.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```


**Returns:**  
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final byte isWriteProtected()
```

바인드된 프레젠테이션이 쓰기 보호되는지 여부를 나타내는 값을 반환합니다.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```


--------------------

프레젠테이션이 열기 비밀번호로 보호된 경우, 속성 값은 NotDefined와 같습니다.

**Returns:**  
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

바인드된 프레젠테이션의 형식을 반환합니다. 읽기 전용 [LoadFormat](../../com.aspose.slides/loadformat).

**Returns:**  
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```

열기 비밀번호로 보호된 프레젠테이션에 대해 비밀번호가 올바른지 확인합니다.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```


**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | 확인할 비밀번호. |

--------------------

password가 null이거나 비어 있으면 이 메서드는 false를 반환합니다.

**Returns:**  
boolean - 프레젠테이션이 열기 비밀번호로 보호되고 비밀번호가 올바른 경우 True, 그 외에는 false를 반환합니다.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

쓰기 보호된 프레젠테이션에 대해 수정 비밀번호가 올바른지 확인합니다.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | 확인할 비밀번호. |

--------------------

1. 이 메서드를 호출하기 전에 (\#isWriteProtected.isWriteProtected) 속성을 확인해야 합니다. 2. password가 null이거나 비어 있으면 이 메서드는 false를 반환합니다.

**Returns:**  
boolean - 프레젠테이션이 쓰기 보호되고 비밀번호가 올바른 경우 True, 그렇지 않으면 False.
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```

바인드된 프레젠테이션의 문서 속성을 가져옵니다.

**Returns:**  
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```

바인드된 프레젠테이션의 속성을 업데이트합니다.

--------------------

> ```
> This sample shows how to call the #updateDocumentProperties(IDDocumentProperties).updateDocumentProperties(IDDocumentProperties) method to
>  update the document properties returned by call of the #readDocumentProperties.readDocumentProperties method.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```


**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |  |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```

바인드된 프레젠테이션을 스트림에 씁니다.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | 스트림은 탐색 가능하고 쓰기 가능해야 합니다. |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```

바인드된 프레젠테이션을 파일에 씁니다.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | 프레젠테이션 파일. |