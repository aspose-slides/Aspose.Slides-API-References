---
title: IProtectionManager
second_title: Aspose.Slides for Java API Reference
description: Presentation password protection management.
type: docs
url: /ko/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

프레젠테이션 비밀번호 보호 관리.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | 프레젠테이션이 비밀번호로 보호된 경우에만 이 속성이 의미가 있습니다. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | 프레젠테이션이 비밀번호로 보호된 경우에만 이 속성이 의미가 있습니다. |
| [isEncrypted()](#isEncrypted--) | 이 인스턴스가 암호화되었는지 여부를 나타내는 값을 가져옵니다. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | 프레젠테이션 파일이 비밀번호로 보호되고 해당 파일의 문서 속성이 공개된 경우에만 이 속성이 의미가 있습니다. |
| [isWriteProtected()](#isWriteProtected--) | 이 프레젠테이션이 쓰기 보호되어 있는지 여부를 나타내는 값을 가져옵니다. |
| [getEncryptionPassword()](#getEncryptionPassword--) | 암호화 비밀번호를 반환합니다. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | 읽기 전용 권장 설정을 가져오거나 설정합니다. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | 읽기 전용 권장 설정을 가져오거나 설정합니다. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | 지정된 비밀번호로 프레젠테이션을 암호화합니다. |
| [removeEncryption()](#removeEncryption--) | 암호화를 제거합니다. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | 지정된 비밀번호로 이 프레젠테이션에 쓰기 보호를 설정합니다. |
| [removeWriteProtection()](#removeWriteProtection--) | 이 프레젠테이션의 쓰기 보호를 제거합니다. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | 프레젠테이션이 수정하기 위해 비밀번호로 보호되는지 여부를 판단합니다. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

프레젠테이션이 비밀번호로 보호된 경우에만 이 속성이 의미가 있습니다. true인 경우 문서 속성이 프레젠테이션 파일에 암호화됩니다. false인 경우 프레젠테이션이 암호화된 동안 문서 속성이 공개됩니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

프레젠테이션이 비밀번호로 보호된 경우에만 이 속성이 의미가 있습니다. true인 경우 문서 속성이 프레젠테이션 파일에 암호화됩니다. false인 경우 프레젠테이션이 암호화된 동안 문서 속성이 공개됩니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

이 인스턴스가 암호화되었는지 여부를 나타내는 값을 가져옵니다. 읽기 전용 boolean.

값: 프레젠테이션이 암호화된 파일에서 로드되었거나 \#encrypt(String).encrypt(String) 메서드가 호출된 경우 true; 그렇지 않으면 false.

**반환값:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

프레젠테이션 파일이 비밀번호로 보호되고 해당 파일의 문서 속성이 공개된 경우에만 이 속성이 의미가 있습니다. true인 경우 비밀번호 없이 암호화된 프레젠테이션 파일에서 문서 속성만 로드됩니다. false인 경우 올바른 비밀번호를 사용해 전체 암호화된 프레젠테이션이 로드되며 문서 속성만 로드되지 않습니다. 프레젠테이션이 암호화되지 않은 경우 속성 값은 항상 false입니다. 암호화된 파일의 문서 속성이 공개되지 않은 경우 속성 값은 항상 false입니다. PresentationEx.EncryptDocumentProperties가 true이면 IsOnlyDocumentPropertiesLoaded 속성 값은 항상 false입니다. 읽기 전용 boolean.

**반환값:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

이 프레젠테이션이 쓰기 보호되어 있는지 여부를 나타내는 값을 가져옵니다. 읽기 전용 boolean.

**반환값:**
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

암호화 비밀번호를 반환합니다. 읽기 전용 String.

**반환값:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

읽기 전용 권장 설정을 가져오거나 설정합니다. 읽기/쓰기 boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**반환값:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```

읽기 전용 권장 설정을 가져오거나 설정합니다. 읽기/쓰기 boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public abstract void encrypt(String encryptionPassword)
```

지정된 비밀번호로 프레젠테이션을 암호화합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| encryptionPassword | java.lang.String | 비밀번호입니다. |

### removeEncryption() {#removeEncryption--}
```
public abstract void removeEncryption()
```

암호화를 제거합니다.

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public abstract void setWriteProtection(String password)
```

지정된 비밀번호로 이 프레젠테이션에 쓰기 보호를 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| password | java.lang.String | 비밀번호입니다. |

### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```

이 프레젠테이션의 쓰기 보호를 제거합니다.

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| password | java.lang.String | 확인할 비밀번호입니다.

--------------------

1. 이 메서드를 호출하기 전에 (\#isWriteProtected.isWriteProtected) 속성을 확인해야 합니다. 2. 비밀번호가 null이거나 비어 있는 경우 이 메서드는 false를 반환합니다.

**반환값:**
boolean - 비밀번호가 유효하면 true; 그렇지 않으면 false.