---
title: MulticastDelegate()
second_title: Aspose.Slides for C++ API Referansı
description: Boş bir koleksiyon oluşturur.
type: docs
weight: 1
url: /tr/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/multicastdelegate/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate() method

Boş bir koleksiyon oluşturur.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate()
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t) method

Varsayılan yapıcıya eşdeğerdir.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t)
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate\&) method

Delegate koleksiyonunun yüzeysel bir kopyasını gerçekleştirir.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate &o)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| o | const MulticastDelegate\& | Delegate koleksiyonunu kopyalamak için MulticastDelegate sınıfının bir örneği. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate\&&) method

Taşıma yapıcısı.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate &&o) noexcept
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| o | MulticastDelegate\&& | Delegate koleksiyonunu taşımak için MulticastDelegate sınıfının bir örneği. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback\&&) method

Bir örnek oluşturur ve belirtilen delegate'i delegate koleksiyonuna ekler.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback &&initial)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| initial | [Callback](../callback/)\&& | Delegate koleksiyonuna eklenecek bir delegate |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(T) method

Bir örnek oluşturur ve belirtilen değeri delegate koleksiyonuna ekler.

```cpp
template<class T,typename> System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(T arg)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Yeni oluşturulan örneğin delegate koleksiyonuna eklenecek değerin türü; bu tür Callback türüne dönüştürülebilir olmalıdır. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg | T | Delegate koleksiyonuna eklenecek bir değer |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function\<ReturnType(ArgumentTypes...)>) method

Bir örnek oluşturur ve belirtilen değeri delegate koleksiyonuna ekler.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function<ReturnType(ArgumentTypes...)> arg)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg | std::function\<ReturnType(ArgumentTypes...)> | Delegate koleksiyonuna eklenecek bir değer |

## Ayrıca Bakınız

* Typedef [Callback](../callback/)
* Sınıf [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* İsim Uzayı [System](../../)
* Kütüphane [Aspose.Slides](../../../)