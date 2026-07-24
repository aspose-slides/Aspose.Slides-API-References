---
title: disconnect()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen temsilciyi temsilci koleksiyonundan kaldırır.
type: docs
weight: 170
url: /tr/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/disconnect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(Callback) metod

Belirtilen temsilciyi temsilci koleksiyonundan kaldırır.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(Callback callback)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| callback | [Callback](../callback/) | Koleksiyondan kaldırılacak temsilci |

### Dönüş Değeri

Kendine bir referans

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, ClassType *) metod

Belirtilen nesnenin belirtilen statik olmayan metodunu temsilci koleksiyonundan kaldırır.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, ClassType *obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| MemberType | Temsilci koleksiyonundan kaldırılacak statik olmayan metodun türü |
| ClassType | Kaldırılacak nesne metodunun türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| member | MemberType ClassType::* | Belirtilen nesnenin statik olmayan metoduna bir işaretçi |
| obj | ClassType * | Temsilci koleksiyonundan kaldırılacak nesne üye metoduna bir işaretçi |

### Dönüş Değeri

Kendine bir referans

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) metod

Belirtilen nesnenin belirtilen statik olmayan metodunu temsilci koleksiyonundan kaldırır.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| MemberType | Temsilci koleksiyonundan kaldırılacak statik olmayan metodun türü |
| ClassType | Kaldırılacak nesne metodunun türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| member | MemberType ClassType::* | Belirtilen nesnenin statik olmayan metoduna bir işaretçi |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Kaldırılacak nesne üye metoduna ait paylaşımlı işaretçi |

### Dönüş Değeri

Kendine bir referans

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate\&) metod

Belirtilen MulticastDelegate nesnesini temsilci koleksiyonundan kaldırır.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate &other)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | Temsilci koleksiyonundan kaldırılacak MulticastDelegate sınıfının bir örneği |

### Dönüş Değeri

Kendine bir referans

## İlgili

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Metod [MulticastDelegate](../multicastdelegate/)
* Sınıf [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* İsim Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)