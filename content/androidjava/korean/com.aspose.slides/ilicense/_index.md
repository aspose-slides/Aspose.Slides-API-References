---
title: ILicense
second_title: Aspose.Slides for Android via Java API Reference
description: 구성 요소에 라이선스를 적용하는 메서드를 제공합니다.
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
| [resetLicense()](#resetLicense--) | 라이선스를 재설정합니다 |
| [isLicensed()](#isLicensed--) | 구성 요소에 라이선스가 적용되었는지 확인합니다 |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| licenseName | java.lang.String | 전체 파일명 또는 짧은 파일명, 또는 임베디드 리소스 이름일 수 있습니다. 빈 문자열을 사용하면 평가 모드로 전환됩니다. |

Tries to find the license in the following locations:

1. 명시적인 경로.

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 라이선스를 포함하는 스트림. |

Use this method to load a license from a stream. |

### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```

라이선스를 재설정합니다

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

--------------------

구성 요소의 라이선스를 재설정하는 데 이 메서드를 사용합니다

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```

구성 요소에 라이선스가 적용되었는지 확인합니다

**반환:**  
boolean - 구성 요소가 라이선스된 경우 true, 그렇지 않으면 false