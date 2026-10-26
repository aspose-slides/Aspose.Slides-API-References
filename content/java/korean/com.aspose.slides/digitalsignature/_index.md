---
title: DigitalSignature
second_title: Java용 Aspose.Slides API 레퍼런스
description: 서명된 파일에 포함된 디지털 서명.
type: docs
url: /ko/com.aspose.slides/digitalsignature/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IDigitalSignature](../../com.aspose.slides/idigitalsignature)
```
public class DigitalSignature implements IDigitalSignature
```

서명된 파일의 디지털 서명.

--------------------

> ```
> The following example demonstrates how to add digital signature from a PFX certificate in PowerPoint Presentation.
>  
>  // Presentation 인스턴스를 초기화합니다
>  Presentation pres = new Presentation();
>  try {
>     // PFX 파일과 PFX 비밀번호로 DigitalSignature 객체를 생성합니다
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      // 새 디지털 서명에 주석을 추가합니다
>      signature.setComments("Aspose.Slides digital signing test.");
>      // 프레젠테이션에 디지털 서명을 추가합니다
>      pres.getDigitalSignatures().add(signature);
>      // 프레젠테이션을 저장합니다
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code demonstrates how to validate digital signature of PowerPoint Presentation.
>  
>  // Presentation 인스턴스를 초기화합니다
>  Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          // 모든 디지털 서명이 유효한지 확인합니다
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>              System.out.println(signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>              allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>              System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>              System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | 지정된 인증서를 사용하여 새 DigitalSignature 객체를 생성합니다. |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | 지정된 인증서 파일 경로와 비밀번호를 사용하여 새 DigitalSignature 객체를 생성합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCertificate()](#getCertificate--) | 문서 서명에 사용된 인증서 객체. |
| [isValid()](#isValid--) | 이 디지털 서명이 유효하고 문서가 변조되지 않은 경우, 이 값은 true가 됩니다. |
| [getSignTime()](#getSignTime--) | 문서가 서명된 시간. |
| [getComments()](#getComments--) | 서명의 목적. |
| [setComments(String value)](#setComments-java.lang.String-) | 서명의 목적. |
### DigitalSignature(byte[] certData, String password) {#DigitalSignature-byte---java.lang.String-}
```
public DigitalSignature(byte[] certData, String password)
```

지정된 인증서를 사용하여 새 DigitalSignature 객체를 생성합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| certData | byte[] | 인증서를 포함하는 바이트 배열 |
| password | java.lang.String | 인증서에 접근하기 위해 필요한 비밀번호. |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```

지정된 인증서 파일 경로와 비밀번호를 사용하여 새 DigitalSignature 객체를 생성합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 인증서가 포함된 파일의 경로. |
| password | java.lang.String | 인증서에 접근하기 위해 필요한 비밀번호. |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```

문서 서명에 사용된 인증서 객체. 읽기 전용 byte[].

**반환값:**
byte[]
### isValid() {#isValid--}
```
public final boolean isValid()
```

이 디지털 서명이 유효하고 문서가 변조되지 않은 경우, 이 값은 true가 됩니다. 읽기 전용 boolean.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.isValid() ? "VALID" : "INVALID"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**
boolean
### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```

문서가 서명된 시간. 읽기 전용 java.util.Date.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.isValid() ? "VALID" : "INVALID") + ", Signing time: " + signature.getSignTime());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**
java.util.Date
### getComments() {#getComments--}
```
public final String getComments()
```

서명의 목적. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

서명의 목적. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |