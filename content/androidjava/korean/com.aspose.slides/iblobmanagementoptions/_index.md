---
title: IBlobManagementOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Binary Large Object(BLOB)은 단일 엔터티로 저장된 바이너리 데이터입니다 - 즉,
type: docs
url: /ko/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

BLOB(바이너리 대용량 객체)는 단일 엔터티로 저장된 바이너리 데이터입니다 - 즉, BLOB은 오디오, 비디오 또는 프레젠테이션 자체가 될 수 있습니다. BLOB과 작업할 때 메모리 사용량을 최적화하기 위해 여러 기술이 사용됩니다 - 이는 이미 프레젠테이션에 저장되어 있거나 나중에 프로그래밍 방식으로 추가될 수 있습니다. [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)를 사용하면 [IPresentation](../../com.aspose.slides/ipresentation) 인스턴스 수명 동안 BLOB 처리와 관련된 다양한 동작 측면을 변경할 수 있습니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | 이 속성은 Presentation 클래스의 인스턴스가 수명 동안 소스(파일 또는 스트림)의 소유자가 될 수 있는지 정의합니다. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | 이 속성은 Presentation 클래스의 인스턴스가 수명 동안 소스(파일 또는 스트림)의 소유자가 될 수 있는지 정의합니다. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | 이 속성은 BLOB 작업 중에 임시 파일을 생성할 수 있는지 정의합니다. 이는 메모리 사용량을 크게 줄이지만 파일 생성 권한이 필요합니다. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | 이 속성은 BLOB 작업 중에 임시 파일을 생성할 수 있는지 정의합니다. 이는 메모리 사용량을 크게 줄이지만 파일 생성 권한이 필요합니다. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | 임시 파일이 생성될 루트 경로입니다. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | 임시 파일이 생성될 루트 경로입니다. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | 메모리 내에서 모든 BLOB이 차지할 수 있는 최대 총 크기(바이트)를 정의합니다. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | 메모리 내에서 모든 BLOB이 차지할 수 있는 최대 총 크기(바이트)를 정의합니다. |

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

이 속성은 Presentation 클래스의 인스턴스가 수명 동안 소스(파일 또는 스트림)의 소유자가 될 수 있는지 정의합니다. 인스턴스가 소유자인 경우 소스를 잠급니다. 이는 BLOB 작업 시 메모리 사용량과 성능을 향상시키지만, Presentation 인스턴스 수명 동안 소스(스트림 또는 파일)를 변경할 수 없게 합니다. 다음은 예시입니다:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // Presentation 수명 동안 pres.pptx가 잠겨 있기 때문에 IOException이 발생합니다.
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // Presentation 객체가 해제된 후 파일이 잠금 해제되어 삭제할 수 있습니다.
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```

**반환값:**
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

이 속성은 Presentation 클래스의 인스턴스가 수명 동안 소스(파일 또는 스트림)의 소유자가 될 수 있는지 정의합니다. 인스턴스가 소유자인 경우 소스를 잠급니다. 이는 BLOB 작업 시 메모리 사용량과 성능을 향상시키지만, Presentation 인스턴스 수명 동안 소스(스트림 또는 파일)를 변경할 수 없게 합니다. 다음은 예시입니다:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException이 발생합니다. 이유는 pres.pptx가 Presentation 수명 동안 잠겨 있기 때문입니다.
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // Presentation 객체가 해제된 후, 파일이 잠금 해제되어 삭제할 수 있습니다.
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

이 속성은 BLOB 작업 중에 임시 파일을 생성할 수 있는지 정의합니다. 이는 메모리 사용량을 크게 줄이지만 파일 생성 권한이 필요합니다.

--------------------

프레젠테이션 작업이 끝난 후 모든 파일이 삭제됩니다.

**반환값:**
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

이 속성은 BLOB 작업 중에 임시 파일을 생성할 수 있는지 정의합니다. 이는 메모리 사용량을 크게 줄이지만 파일 생성 권한이 필요합니다.

--------------------

프레젠테이션 작업이 끝난 후 모든 파일이 삭제됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

임시 파일이 생성될 루트 경로입니다. 기본적으로 시스템 임시 디렉터리가 사용됩니다. 호스팅 프로세스는 해당 위치에 파일 및 폴더를 생성할 권한이 있어야 합니다.

**반환값:**
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

임시 파일이 생성될 루트 경로입니다. 기본적으로 시스템 임시 디렉터리가 사용됩니다. 호스팅 프로세스는 해당 위치에 파일 및 폴더를 생성할 권한이 있어야 합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

이 속성은 메모리 내에서 모든 BLOB이 차지할 수 있는 최대 총 크기(바이트)를 정의합니다. 기본적으로 모든 BLOB은 메모리에 로드되며, 이 제한에 도달하면 임시 파일과 같은 대체 메커니즘이 사용됩니다. BLOB을 메모리에 유지하면 성능이 최적화되지만 메모리 사용량이 크게 증가할 수 있습니다. 이 속성을 사용하여 환경이나 요구 사항에 맞게 동작을 조정하십시오.

--------------------

이 속성은 \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean)가 false로 설정된 경우 무시됩니다. 이는 메모리가 유일한 저장소가 되어 인메모리 BLOB 사용량 제한이 효과가 없기 때문입니다.

--------------------

기본값은 629,145,600 바이트(600 MB)입니다.

--------------------

이 속성을 0으로 설정할 수 있지만, 작은 최소 메모리는 여전히 예약됩니다.

**반환값:**
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

이 속성은 메모리 내에서 모든 BLOB이 차지할 수 있는 최대 총 크기(바이트)를 정의합니다. 기본적으로 모든 BLOB은 메모리에 로드되며, 이 제한에 도달하면 임시 파일과 같은 대체 메커니즘이 사용됩니다. BLOB을 메모리에 유지하면 성능이 최적화되지만 메모리 사용량이 크게 증가할 수 있습니다. 이 속성을 사용하여 환경이나 요구 사항에 맞게 동작을 조정하십시오.

--------------------

이 속성은 \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean)가 false로 설정된 경우 무시됩니다. 이는 메모리가 유일한 저장소가 되어 인메모리 BLOB 사용량 제한이 효과가 없기 때문입니다.

--------------------

기본값은 629,145,600 바이트(600 MB)입니다.

--------------------

이 속성을 0으로 설정할 수 있지만, 작은 최소 메모리는 여전히 예약됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | long |  |