---
title: ProtectionManager
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 프레젠테이션 비밀번호 보호 관리.
type: docs
url: /ko/com.aspose.slides/protectionmanager/
---
**상속:**  
java.lang.Object

**전체 구현된 인터페이스:**  
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)  
```
public final class ProtectionManager implements IProtectionManager
```

프레젠테이션 비밀번호 보호 관리.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | 이 속성은 프레젠테이션이 비밀번호로 보호된 경우에 의미가 있습니다. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | 이 속성은 프레젠테이션이 비밀번호로 보호된 경우에 의미가 있습니다. |
| [isEncrypted()](#isEncrypted--) | 이 인스턴스가 암호화되었는지 여부를 나타내는 값을 가져옵니다. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | 이 속성은 프레젠테이션 파일이 비밀번호로 보호되고 해당 파일의 문서 속성이 공개된 경우에 의미가 있습니다. |
| [isWriteProtected()](#isWriteProtected--) | 이 프레젠테이션이 쓰기 보호되는지 여부를 나타내는 값을 가져옵니다. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | 지정된 비밀번호로 프레젠테이션을 암호화합니다. |
| [removeEncryption()](#removeEncryption--) | 암호화를 제거합니다. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | 지정된 비밀번호로 이 프레젠테이션에 쓰기 보호를 설정합니다. |
| [removeWriteProtection()](#removeWriteProtection--) | 이 프레젠테이션에 대한 쓰기 보호를 제거합니다. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | 프레젠테이션이 수정하기 위해 비밀번호로 보호되는지 여부를 판단합니다. |
| [getEncryptionPassword()](#getEncryptionPassword--) | 프레젠테이션 암호화에 사용되는 비밀번호를 가져옵니다. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | 읽기 전용 권고를 가져오거나 설정합니다. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | 읽기 전용 권고를 가져오거나 설정합니다. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

이 속성은 프레젠테이션이 비밀번호로 보호된 경우에 의미가 있습니다. true인 경우 문서 속성이 프레젠테이션 파일에 암호화됩니다. false인 경우 프레젠테이션이 암호화된 상태에서도 문서 속성이 공개됩니다. 읽기/쓰기 부울.

**반환:**  
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

이 속성은 프레젠테이션이 비밀번호로 보호된 경우에 의미가 있습니다. true인 경우 문서 속성이 프레젠테이션 파일에 암호화됩니다. false인 경우 프레젠테이션이 암호화된 상태에서도 문서 속성이 공개됩니다. 읽기/쓰기 부울.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

이 인스턴스가 암호화되었는지 여부를 나타내는 값을 가져옵니다. 읽기 전용 부울.

값: 프레젠테이션이 암호화된 파일에서 로드되었거나 \#encrypt(String).encrypt(String) 메서드가 호출된 경우 true; 그렇지 않으면 false.

**반환:**  
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

이 속성은 프레젠테이션 파일이 비밀번호로 보호되고 해당 파일의 문서 속성이 공개된 경우에 의미가 있습니다. true인 경우 비밀번호 없이 암호화된 프레젠테이션 파일에서 문서 속성만 로드된다는 의미입니다. false인 경우 올바른 비밀번호를 사용하여 전체 암호화된 프레젠테이션이 로드되며, 문서 속성만 로드되는 것이 아닙니다. 프레젠테이션이 암호화되지 않은 경우 속성 값은 항상 false입니다. 암호화된 파일의 문서 속성이 공개되지 않은 경우에도 속성 값은 항상 false입니다. Presentation.EncryptDocumentProperties가 true이면 IsOnlyDocumentPropertiesLoaded 속성 값은 항상 false입니다. 읽기 전용 부울.

**반환:**  
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

이 프레젠테이션이 쓰기 보호되는지 여부를 나타내는 값을 가져옵니다. 읽기 전용 부울.

**반환:**  
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```

지정된 비밀번호로 프레젠테이션을 암호화합니다.

--------------------

> ```
> The following sample code shows you how to encrypt a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().encrypt("123123");
>      pres.save("encrypted-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| encryptionPassword | java.lang.String | 비밀번호. |
### removeEncryption() {#removeEncryption--}
```
public final void removeEncryption()
```

암호화를 제거합니다.

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```

지정된 비밀번호로 이 프레젠테이션에 쓰기 보호를 설정합니다.

--------------------

> ```
> 다음 샘플 코드는 프레젠테이션에 쓰기 보호를 설정하는 방법을 보여 줍니다.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().setWriteProtection("123123");
>      pres.save("write-protected-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| password | java.lang.String | 비밀번호. |
### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```

이 프레젠테이션에 대한 쓰기 보호를 제거합니다.

--------------------

> ```
> 이 샘플 코드는 PowerPoint 프레젠테이션에서 쓰기 보호를 제거하는 방법을 보여 줍니다.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().removeWriteProtection();
>      pres.save("write-protection-removed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

프레젠테이션이 수정하기 위해 비밀번호로 보호되는지 여부를 판단합니다.

--------------------

> ```
> Presentation presentation = new Presentation(presentationFilePath);
>  try {
>      boolean isWriteProtected = presentation.getProtectionManager().checkWriteProtection("my_password");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| password | java.lang.String | 확인용 비밀번호. |

--------------------

1. 이 메서드를 호출하기 전에 (\#isWriteProtected.isWriteProtected) 속성을 확인해야 합니다.  
2. 비밀번호가 null이거나 빈 문자열인 경우, 이 메서드는 false를 반환합니다.  

**반환:**  
boolean - 비밀번호가 유효하면 true; 그렇지 않으면 false.
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```

프레젠테이션 암호화에 사용되는 비밀번호를 가져옵니다. 읽기 전용 문자열.

**반환:**  
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```

읽기 전용 권고를 가져오거나 설정합니다. 읽기/쓰기 부울.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환:**  
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)
```

읽기 전용 권고를 가져오거나 설정합니다. 읽기/쓰기 부울.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |