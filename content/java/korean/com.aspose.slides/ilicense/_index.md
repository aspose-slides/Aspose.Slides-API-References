---
title: ILicense
second_title: Aspose.Slides for Java API Reference
description: Provides methods to license the component.
type: docs
url: /ko/com.aspose.slides/ilicense/
---```
public interface ILicense
```

구성 요소에 라이선스를 적용하는 메서드를 제공합니다.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | 구성 요소에 라이선스를 적용합니다. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | 구성 요소에 라이선스를 적용합니다. |
| [resetLicense()](#resetLicense--) | 라이선스를 재설정합니다. |
| [isLicensed()](#isLicensed--) | 구성 요소에 라이선스가 적용되었는지 확인합니다. |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```


구성 요소에 라이선스를 적용합니다.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| licenseName | java.lang.String | 전체 파일 이름이거나 짧은 파일 이름, 또는 임베디드 리소스의 이름일 수 있습니다. 빈 문자열을 사용하면 평가 모드로 전환됩니다.

--------------------

다음 위치에서 라이선스를 찾습니다:

1. 명시적 경로.

2. 구성 요소 어셈블리의 폴더.

3. 클라이언트 호출 어셈블리의 폴더.

4. 엔트리 어셈블리의 폴더.

5. 클라이언트 호출 어셈블리의 임베디드 리소스. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```


구성 요소에 라이선스를 적용합니다.

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 라이선스를 포함하는 스트림입니다.

--------------------

이 메서드를 사용하여 스트림에서 라이선스를 로드합니다. |

### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```


라이선스를 재설정합니다.

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

--------------------

이 메서드를 사용하여 구성 요소의 라이선스를 재설정합니다.

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```


구성 요소에 라이선스가 적용되었는지 확인합니다.

**반환값:**
boolean - 구성 요소에 라이선스가 적용되면 true, 그렇지 않으면 false