---
title: OperatingSystem
second_title: Aspose.Slides for C++ API 레퍼런스
description: "특정 운영 체제를 나타내며 해당에 대한 정보를 제공합니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하여 인스턴스를 만들지 마십시오. 이렇게 하면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 해당 포인터를 함수 인수로 전달하십시오."
type: docs
weight: 1171
url: /ko/system/operatingsystem/
---
## OperatingSystem 클래스

특정 운영 체제를 나타내며 해당에 대한 정보를 제공합니다. 이 클래스의 객체는 [System::MakeObject()](../makeobject/) 함수를 사용하여 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하여 인스턴스를 만들지 마십시오. 이렇게 하면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 [System::SmartPtr](../smartptr/) 포인터로 감싸고, 해당 포인터를 함수 인수로 전달하십시오.

```cpp
class OperatingSystem
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [PlatformID](../platformid/) [get_Platform](./get_platform/)() const | 현재 객체가 나타내는 운영 체제의 플랫폼 식별자를 반환합니다. |
| [String](../string/) [get_ServicePack](./get_servicepack/)() const | 현재 객체가 나타내는 운영 체제의 서비스 팩 이름을 반환합니다. |
| const [Version](../version/)\& [get_Version](./get_version/)() const | 현재 객체가 나타내는 운영 체제 버전을 나타내는 [Version](../version/) 객체에 대한 상수 참조를 반환합니다. |
| [String](../string/) [get_VersionString](./get_versionstring/)() const | 현재 객체가 나타내는 운영 체제 버전의 문자열 표현을 반환합니다. |
| static **bool** [IsFreeBSD](./isfreebsd/)() | 현재 애플리케이션이 FreeBSD에서 실행 중인지 여부를 나타냅니다. |
| static **bool** [IsLinux](./islinux/)() | 현재 애플리케이션이 Linux에서 실행 중인지 여부를 나타냅니다. |
| static **bool** [IsMacOS](./ismacos/)() | 현재 애플리케이션이 MacOS에서 실행 중인지 여부를 나타냅니다. |
| static **bool** [IsOSPlatform](./isosplatform/)(const [String](../string/)\&) | 현재 애플리케이션이 지정된 플랫폼에서 실행 중인지 여부를 나타냅니다. |
| static **bool** [IsWindows](./iswindows/)() | 현재 애플리케이션이 [Windows](../../system.windows/)에서 실행 중인지 여부를 나타냅니다. |
|  [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&) | 특정 플랫폼 ID와 버전으로 지정된 운영 체제를 나타내는 인스턴스를 생성합니다. |
|  [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&, const [String](../string/)\&) | 특정 플랫폼 ID, 버전 및 서비스 팩으로 지정된 운영 체제를 나타내는 인스턴스를 생성합니다. |
| [String](../string/) [ToString](./tostring/)() const | 현재 객체가 나타내는 운영 체제 버전의 문자열 표현을 반환합니다. |

## 참조

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)