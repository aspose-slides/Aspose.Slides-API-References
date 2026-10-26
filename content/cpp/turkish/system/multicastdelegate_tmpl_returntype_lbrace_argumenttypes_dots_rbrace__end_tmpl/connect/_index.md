---
title: connect()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen temsilciyi koleksiyona ekler.
type: docs
weight: 144
url: /tr/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/connect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(Callback) yöntemi


Belirtilen temsilciyi koleksiyona ekler.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(Callback callback)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| callback | [Callback](../callback/) | Koleksiyona eklenmek üzere temsilci |

### Dönüş Değeri

Kendisine bir başvuru

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(std::function\<R(Args...)>) yöntemi


Belirtilen fonksiyon nesnesini temsilci koleksiyonuna ekler. Fonksiyon nesnesi, koleksiyona eklenmeden önce Callback temsilci tipine dönüştürülür.

```cpp
template<class R,class...> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(std::function<R(Args...)> f)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| R | Koleksiyona eklenecek fonksiyon nesnesinin dönüş tipi |
| Args | Koleksiyona eklenecek fonksiyon nesnesinin parametre listesi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| f | std::function\<R(Args...)> | Koleksiyona eklenmek üzere fonksiyon nesnesi |

### Dönüş Değeri

Kendisine bir başvuru

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MulticastDelegate\&) yöntemi


Belirtilen MulticastDelegate nesnesini temsilci koleksiyonuna ekler.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MulticastDelegate &other)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | delegate koleksiyonuna eklenecek MulticastDelegate sınıfının bir örneği |

### Dönüş Değeri

Kendisine bir başvuru

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, ClassType *) yöntemi


Belirtilen nesnenin belirtilen statik olmayan metodunu delegate koleksiyonuna ekler.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, ClassType *obj)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| MemberType | Delegate koleksiyonuna eklenmek üzere statik olmayan metodun tipi |
| ClassType | Delegate koleksiyonuna eklenmek üzere nesnenin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| member | MemberType ClassType::* | Belirtilen nesnenin statik olmayan metoduna işaretçi |
| obj | ClassType * | Delegate koleksiyonuna eklenmek üzere nesne üye metoduna işaretçi |

### Dönüş Değeri

Kendisine bir başvuru

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) yöntemi


Belirtilen nesnenin belirtilen statik olmayan metodunu delegate koleksiyonuna ekler.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| MemberType | Delegate koleksiyonuna eklenmek üzere statik olmayan metodun tipi |
| ClassType | Delegate koleksiyonuna eklenmek üzere nesnenin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| member | MemberType ClassType::* | Belirtilen nesnenin statik olmayan metoduna işaretçi |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Delegate koleksiyonuna eklenmek üzere nesne üye metoduna işaret eden paylaşımlı işaretçi |

### Dönüş Değeri

Kendisine bir başvuru

## Ayrıca Bakınız

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [MulticastDelegate](../multicastdelegate/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)