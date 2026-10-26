---
title: Delegate()
second_title: Aspose.Slides for C++ API Referansı
description: Varsayılan yapıcı. Bir şeye işaret etmeyen delegate nesnesini oluşturur.
type: docs
weight: 1
url: /tr/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/delegate/
---
## Delegate< ReturnType(ArgumentTypes...)>::Delegate() metodu

Varsayılan yapıcı. Bir şeye işaret etmeyen delegate nesnesini oluşturur.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate()=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(const Delegate\&) metodu

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(const Delegate &)=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(Delegate\&&) metodu

Taşıma kopya yapıcı. Belirtilen delegate tarafından işaret edilen varlığın sahipliğini devralır.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(Delegate &&o) noexcept
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| o | Delegate\&& | İşaret edilen varlığı taşıyacak Delegate nesnesi |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) metodu

Yapıcı. Belirtilen serbest işlev ya da statik metoda işaret eden işaretçiden bir delegate nesnesi oluşturur.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<!std::is_bind_expression<T>::value &&std::is_pointer<T>::value &&std::is_function<typename std::remove_pointer<T>::type>::value>::type *=0)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| The | Yapıcı tarafından argüman olarak kabul edilen fonksiyon ya da statik metod işaretçisinin tipi |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| function | T | Yeni oluşturulan Delegate örneğinin işaret edeceği bir fonksiyon veya statik metoda işaretçi |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) metodu

Yapıcı. std::bind() tarafından oluşturulan işlev nesnesine işaret eden belirtilen işaretçiden bir delegate oluşturur.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<std::is_bind_expression<T>::value>::type *=0)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| The | Yapıcı tarafından argüman olarak kabul edilen std::bind() ile oluşturulan işlev nesnesinin tipi |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| function | T | Yeni oluşturulan Delegate örneğinin işaret edeceği bir "bind ifadesi" - std::bind() tarafından oluşturulan bir fonksiyon işaretçisi |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(int, T\&) metodu

Yapıcı. Belirtilen işlev nesnesinden bir delegate oluşturur.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(int functor_tag, T &functor)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Yapıcı tarafından argüman olarak kabul edilen işlev nesnesinin tipi |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functor_tag | int | Bir sahte tamsayı değeri; bu argüman belirsizliği çözmek için kullanılır |
| functor | T\& | Yeni oluşturulan delegate'in işaret edeceği bir işlev nesnesi |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(long, T\&&) metodu

Taşıma yapıcı. Belirtilen işlev nesnesinden bir delegate oluşturur.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(long functor_tag, T &&functor)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Yapıcı tarafından argüman olarak kabul edilen işlev nesnesinin tipi |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| functor_tag | long | Bir sahte tamsayı değeri; bu argüman belirsizliği çözmek için kullanılır |
| functor | T\&& | Yeni oluşturulan delegate'in işaret edeceği bir işlev nesnesi |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*, ClassType *) metodu

Yapıcı. Belirtilen nesnenin belirtilen statik olmayan metoduna işaret eden bir delegate oluşturur.

```cpp
template<class MemberType,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*member, ClassType *obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| MemberType | Yapıcı tarafından argüman olarak kabul edilen statik olmayan metodun tipi |
| ClassType | Yapıcı tarafından argüman olarak kabul edilen nesnenin tipi |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| member | MemberType ClassType::* | Yeni oluşturulan delegate'in işaret edeceği statik olmayan metoda işaretçi |
| obj | ClassType * | Yeni oluşturulan delegate'in işaret edeceği nesne üye metoduna işaretçi |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*, const SharedPtr\<ClassType\>\&) metodu

Yapıcı. Belirtilen nesnenin belirtilen statik olmayan metoduna işaret eden bir delegate oluşturur.

```cpp
template<class MemberType,class MemberClass,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*member, const SharedPtr<ClassType> &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| MemberType | Yapıcı tarafından argüman olarak kabul edilen statik olmayan metodun tipi |
| ClassType | Yapıcı tarafından argüman olarak kabul edilen nesnenin tipi |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| member | MemberType MemberClass::* | Yeni oluşturulan delegate'in işaret edeceği statik olmayan metoda işaretçi |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Yeni oluşturulan delegate'in işaret edeceği nesne üye metoduna bir paylaşımlı işaretçi |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(std::function\<R(Args...)>) metodu

Bir std::function işlev nesnesine işaret eden bir delegate nesnesi oluşturur.

```cpp
template<class R,class...> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(std::function<R(Args...)> f)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| R | Yapıcı tarafından argüman olarak kabul edilen işlev nesnesinin dönüş tipi |
| Args | Yapıcı tarafından argüman olarak kabul edilen işlev nesnesinin parametre listesi |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| f | std::function\<R(Args...)> | Yeni oluşturulan delegate nesnesinin işaret edeceği bir işlev nesnesi |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [Delegate< ReturnType(ArgumentTypes...)>](../)
* Ad Alanı [System](../../)
* Library [Aspose.Slides](../../../)