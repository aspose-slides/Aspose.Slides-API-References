---
title: OperatingSystem
second_title: Aspose.Slides için C++ API Referansı
description: "Belirli bir işletim sistemini temsil eder ve onun hakkında bilgi sağlar. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu türün örneğini istif üzerinde veya operator new kullanarak asla oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 1171
url: /tr/system/operatingsystem/
---
## OperatingSystem sınıfı

Belirli bir işletim sistemini temsil eder ve onun hakkında bilgi sağlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün örneğini istif üzerinde veya operator new kullanarak asla oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../smartptr/) işaretçisi içine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçmek için kullanın.

```cpp
class OperatingSystem
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [PlatformID](../platformid/) [get_Platform](./get_platform/)() const | Mevcut nesne tarafından temsil edilen işletim sisteminin platform tanımlayıcısını döndürür. |
| [String](../string/) [get_ServicePack](./get_servicepack/)() const | Mevcut nesne tarafından temsil edilen işletim sisteminin servis paketi adını döndürür. |
| const [Version](../version/)\& [get_Version](./get_version/)() const | Mevcut nesne tarafından temsil edilen işletim sisteminin sürümünü temsil eden bir [Version](../version/) nesnesine sabit bir referans döndürür. |
| [String](../string/) [get_VersionString](./get_versionstring/)() const | Mevcut nesne tarafından temsil edilen işletim sisteminin sürümünün dize temsili döndürülür. |
| static **bool** [IsFreeBSD](./isfreebsd/)() | Mevcut uygulamanın FreeBSD üzerinde çalışıp çalışmadığını gösterir. |
| static **bool** [IsLinux](./islinux/)() | Mevcut uygulamanın Linux üzerinde çalışıp çalışmadığını gösterir. |
| static **bool** [IsMacOS](./ismacos/)() | Mevcut uygulamanın MacOS üzerinde çalışıp çalışmadığını gösterir. |
| static **bool** [IsOSPlatform](./isosplatform/)(const [String](../string/)\&) | Mevcut uygulamanın belirtilen platformda çalışıp çalışmadığını gösterir. |
| static **bool** [IsWindows](./iswindows/)() | Mevcut uygulamanın [Windows](../../system.windows/) üzerinde çalışıp çalışmadığını gösterir. |
|  [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&) | Belirli bir platform kimliği ve sürümü ile belirtilen bir işletim sistemini temsil eden bir örnek oluşturur. |
|  [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&, const [String](../string/)\&) | Belirli bir platform kimliği, sürüm ve servis paketi ile belirtilen bir işletim sistemini temsil eden bir örnek oluşturur. |
| [String](../string/) [ToString](./tostring/)() const | Mevcut nesne tarafından temsil edilen işletim sisteminin sürümünün dize temsili döndürülür. |

## Ayrıca Bakınız

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)