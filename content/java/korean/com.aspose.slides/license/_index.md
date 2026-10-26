---
title: License
second_title: Aspose.Slides for Java API 레퍼런스
description: 구성 요소에 대한 라이선스를 부여하는 메서드를 제공합니다.
type: docs
url: /ko/com.aspose.slides/license/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.ILicense](../../com.aspose.slides/ilicense)
```
public final class License implements ILicense
```

구성 요소에 대한 라이선스를 부여하는 메서드를 제공합니다.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [License()](#License--) | 이 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | 구성 요소에 라이선스를 적용합니다. |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | 구성 요소에 라이선스를 적용합니다. |
| [getVersion()](#getVersion--) | Aspose.Slides for Java의 버전을 반환합니다. |
| [resetLicense()](#resetLicense--) | 라이선스를 재설정합니다. |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```


이 클래스의 새 인스턴스를 초기화합니다.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```


구성 요소에 라이선스를 적용합니다.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 라이선스를 포함하는 스트림입니다. null을 사용하여 평가 모드로 전환합니다. |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```


구성 요소에 라이선스를 적용합니다.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| namePath | java.lang.String | 전체 파일 이름이거나 짧은 파일 이름, 또는 포함된 리소스의 이름이 될 수 있습니다. 빈 문자열을 사용하여 평가 모드로 전환합니다. |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```


Aspose.Slides for Java의 버전을 반환합니다.

**반환값:**
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```


라이선스를 재설정합니다. 이 메서드를 사용하여 구성 요소의 라이선스를 재설정하십시오.

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```


구성 요소에 라이선스가 적용되었는지 확인합니다.

**반환값:**
boolean