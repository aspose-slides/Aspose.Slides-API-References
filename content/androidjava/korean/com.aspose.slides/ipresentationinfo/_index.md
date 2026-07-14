---
title: IPresentationInfo
second_title: Aspose.Slides for Android via Java API Reference
description: Information about presentation file
type: docs
url: /ko/com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

프레젠테이션 파일에 대한 정보
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | 바인딩된 프레젠테이션이 암호화된 경우 True를, 그렇지 않으면 False를 반환합니다. |
| [isPasswordProtected()](#isPasswordProtected--) | 바인딩된 프레젠테이션이 열기 비밀번호로 보호되는지 여부를 나타내는 값을 반환합니다. |
| [isWriteProtected()](#isWriteProtected--) | 바인딩된 프레젠테이션이 쓰기 보호되는지 여부를 나타내는 값을 반환합니다. |
| [getLoadFormat()](#getLoadFormat--) | 바인딩된 프레젠테이션의 형식을 반환합니다. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | 열기 비밀번호로 보호된 프레젠테이션에 대한 비밀번호가 올바른지 확인합니다. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | 쓰기 보호된 프레젠테이션에 대한 수정 비밀번호가 올바른지 확인합니다. |
| [readDocumentProperties()](#readDocumentProperties--) | 바인딩된 프레젠테이션의 문서 속성을 반환합니다. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | 바인딩된 프레젠테이션의 속성을 업데이트합니다. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | 바인딩된 프레젠테이션을 스트림에 씁니다. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | 바인딩된 프레젠테이션을 파일에 씁니다. |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

바인딩된 프레젠테이션이 암호화된 경우 True를, 그렇지 않으면 False를 반환합니다. 읽기 전용 boolean.

**반환:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

바인딩된 프레젠테이션이 열기 비밀번호로 보호되는지 여부를 나타내는 값을 반환합니다.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by a password to open.");
>  }
> ```

**반환:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract byte isWriteProtected()
```

바인딩된 프레젠테이션이 쓰기 보호되는지 여부를 나타내는 값을 반환합니다.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```

--------------------

프레젠테이션이 열기 비밀번호로 보호된 경우, 속성 값은 NotDefined와 같습니다. [NullableBool](../../com.aspose.slides/nullablebool) 열거형을 참조하십시오.

**반환:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

바인딩된 프레젠테이션의 형식을 반환합니다. 읽기 전용 [LoadFormat](../../com.aspose.slides/loadformat).

**반환:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```

열기 비밀번호로 보호된 프레젠테이션에 대한 비밀번호가 올바른지 확인합니다.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | 확인할 비밀번호.

--------------------

비밀번호가 null이거나 빈 문자열인 경우, 이 메서드는 false를 반환합니다. |

**반환:**
boolean - 프레젠테이션이 열기 비밀번호로 보호되고 비밀번호가 올바른 경우 True를, 그렇지 않은 경우 false를 반환합니다.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

쓰기 보호된 프레젠테이션에 대한 수정 비밀번호가 올바른지 확인합니다.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | 확인할 비밀번호.

--------------------

1. 이 메서드를 호출하기 전에 (\#isWriteProtected.isWriteProtected) 속성을 확인해야 합니다. 2. 비밀번호가 null이거나 빈 문자열인 경우, 이 메서드는 false를 반환합니다. |

**반환:**
boolean - 프레젠테이션이 쓰기 보호되고 비밀번호가 올바른 경우 True를 반환합니다. 그렇지 않으면 False를 반환합니다.
### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```

바인딩된 프레젠테이션의 문서 속성을 반환합니다.

**반환:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - 문서 속성 [IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public abstract void updateDocumentProperties(IDocumentProperties documentProperties)
```

바인딩된 프레젠테이션의 속성을 업데이트합니다.

--------------------

> ```
> This sample shows how to call the #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) method to
>  update the document properties returned by call of the #readDocumentProperties.readDocumentProperties method.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | 문서 속성 [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```

바인딩된 프레젠테이션을 스트림에 씁니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | 스트림은 검색 가능하고 쓰기 가능해야 합니다.

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```

바인딩된 프레젠테이션을 파일에 씁니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | 프레젠테이션 파일.