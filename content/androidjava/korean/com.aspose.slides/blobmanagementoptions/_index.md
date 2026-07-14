---
title: BlobManagementOptions
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: BLOB 처리 규칙 및 기타 BLOB 설정을 관리하는 데 사용할 수 있는 옵션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/blobmanagementoptions/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)  
```
public class BlobManagementOptions implements IBlobManagementOptions
```

BLOB 처리 규칙 및 기타 BLOB 설정을 관리하는 데 사용할 수 있는 옵션을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | 새 기본 blob 관리 옵션을 생성합니다. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | 이 속성은 Presentation 클래스의 인스턴스가 수명 동안 소스 파일 또는 스트림의 소유자가 될 수 있는지를 정의합니다. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | 이 속성은 Presentation 클래스의 인스턴스가 수명 동안 소스 파일 또는 스트림의 소유자가 될 수 있는지를 정의합니다. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | 이 속성은 BLOB 작업 중에 임시 파일을 생성할 수 있는지를 정의합니다. 이는 메모리 사용량을 크게 줄이지만 파일 생성 권한이 필요합니다. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | 이 속성은 BLOB 작업 중에 임시 파일을 생성할 수 있는지를 정의합니다. 이는 메모리 사용량을 크게 줄이지만 파일 생성 권한이 필요합니다. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | 임시 파일이 생성될 루트 경로. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | 임시 파일이 생성될 루트 경로. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | 모든 BLOB이 메모리에서 차지할 수 있는 총 최대 크기(바이트)를 정의합니다. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | 모든 BLOB이 메모리에서 차지할 수 있는 총 최대 크기(바이트)를 정의합니다. |

### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```

새 기본 blob 관리 옵션을 생성합니다.

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```

이 속성은 Presentation 클래스의 인스턴스가 수명 동안 소스 파일 또는 스트림의 소유자가 될 수 있는지를 정의합니다. 인스턴스가 소유자인 경우 소스를 잠급니다. 이는 BLOB 작업 시 메모리 사용량과 성능을 향상시키지만, Presentation 인스턴스 수명 동안 소스(스트림 또는 파일)를 변경할 수 없습니다.

**반환값:**  
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```

이 속성은 Presentation 클래스의 인스턴스가 수명 동안 소스 파일 또는 스트림의 소유자가 될 수 있는지를 정의합니다. 인스턴스가 소유자인 경우 소스를 잠급니다. 이는 BLOB 작업 시 메모리 사용량과 성능을 향상시키지만, Presentation 인스턴스 수명 동안 소스(스트림 또는 파일)를 변경할 수 없습니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```

이 속성은 BLOB 작업 중에 임시 파일을 생성할 수 있는지를 정의합니다. 이는 메모리 사용량을 크게 줄이지만 파일 생성 권한이 필요합니다.

--------------------

프레젠테이션 작업이 완료된 후 모든 파일이 삭제됩니다.

**반환값:**  
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```

이 속성은 BLOB 작업 중에 임시 파일을 생성할 수 있는지를 정의합니다. 이는 메모리 사용량을 크게 줄이지만 파일 생성 권한이 필요합니다.

--------------------

프레젠테이션 작업이 완료된 후 모든 파일이 삭제됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```

임시 파일이 생성될 루트 경로. 기본적으로 System 임시 디렉터리가 사용됩니다. 호스팅 프로세스는 해당 위치에 파일과 폴더를 생성할 수 있는 권한이 있어야 합니다.

**반환값:**  
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```

임시 파일이 생성될 루트 경로. 기본적으로 System 임시 디렉터리가 사용됩니다. 호스팅 프로세스는 해당 위치에 파일과 폴더를 생성할 수 있는 권한이 있어야 합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```

모든 BLOB이 메모리에서 차지할 수 있는 총 최대 크기(바이트)를 정의합니다. 기본적으로 모든 BLOB이 메모리에 로드되며, 이 한도에 도달하면 임시 파일과 같은 대체 메커니즘이 사용됩니다. BLOB을 메모리에 유지하면 성능이 최적화되지만 메모리 사용량이 급증할 수 있습니다. 환경이나 요구 사항에 맞게 동작을 조정하려면 이 속성을 사용하십시오.

--------------------

이 속성은 \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) 가 false 로 설정된 경우 무시됩니다. 이 경우 메모리만 사용 가능한 저장소가 되며, 인메모리 BLOB 사용을 제한해도 효과가 없습니다.

--------------------

기본값은 629,145,600 바이트(600 MB)입니다.

--------------------

이 속성을 0으로 설정할 수 있지만, 최소한의 메모리는 계속 예약됩니다.

**반환값:**  
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```

모든 BLOB이 메모리에서 차지할 수 있는 총 최대 크기(바이트)를 정의합니다. 기본적으로 모든 BLOB이 메모리에 로드되며, 이 한도에 도달하면 임시 파일과 같은 대체 메커니즘이 사용됩니다. BLOB을 메모리에 유지하면 성능이 최적화되지만 메모리 사용량이 급증할 수 있습니다. 환경이나 요구 사항에 맞게 동작을 조정하려면 이 속성을 사용하십시오.

--------------------

이 속성은 \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) 가 false 로 설정된 경우 무시됩니다. 이 경우 메모리만 사용 가능한 저장소가 되며, 인메모리 BLOB 사용을 제한해도 효과가 없습니다.

--------------------

기본값은 629,145,600 바이트(600 MB)입니다.

--------------------

이 속성을 0으로 설정할 수 있지만, 최소한의 메모리는 계속 예약됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | long |  |