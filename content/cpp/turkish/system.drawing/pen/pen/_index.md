---
title: Pen()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen rengi temsil eden yeni bir Pen nesnesi oluşturur.
type: docs
weight: 1
url: /tr/system.drawing/pen/pen/
---
## Pen::Pen(const Color\&) yapıcı

Belirtilen rengi temsil eden yeni [Pen](../) nesnesini oluşturur.

```cpp
System::Drawing::Pen::Pen(const Color &color)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| color | const [Color](../../color/)\& | Oluşturulan nesne tarafından temsil edilen kalemin rengi |

## Pen::Pen(const Color\&, float) yapıcı

Belirtilen rengi ve genişliği temsil eden yeni [Pen](../) nesnesini oluşturur.

```cpp
System::Drawing::Pen::Pen(const Color &color, float width)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| color | const [Color](../../color/)\& | Oluşturulan nesne tarafından temsil edilen kalemin rengi |
| width | **float** | Oluşturulan nesne tarafından temsil edilen kalemin genişliği |

## Pen::Pen(const SharedPtr\<Brush\>\&) yapıcı

Belirtilen [Brush](../../brush/) nesnesiyle yeni bir [Pen](../) nesnesi oluşturur ve onu başlatır.

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Oluşturulan nesne tarafından temsil edilen kalemin dolgu özelliklerini belirten [Brush](../../brush/) nesnesi |

## Pen::Pen(const SharedPtr\<Brush\>\&, float) yapıcı

Belirtilen [Brush](../../brush/) nesnesiyle yeni bir [Pen](../) nesnesi oluşturur ve onu başlatır.

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush, float width)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Oluşturulan nesne tarafından temsil edilen kalemin dolgu özelliklerini belirten [Brush](../../brush/) nesnesi |
| width | **float** | Oluşturulan nesne tarafından temsil edilen kalemin genişliği |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Color](../../color/)
* Class [Pen](../)
* Class [Brush](../../brush/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)