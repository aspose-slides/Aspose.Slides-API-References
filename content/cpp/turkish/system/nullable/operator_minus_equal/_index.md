---
title: operator-=()
second_title: Aspose.Slides for C++ API Referansı
description: Nullable sınıfının null değerini temsil eden bir örneğini döndürür.
type: docs
weight: 248
url: /tr/system/nullable/operator_minus_equal/
---
## Nullable::operator-=(T1) method

[Nullable](../) sınıfının null değerini temsil eden bir örneğini döndürür.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-=(T1)
```

## Nullable::operator-=(const T1\&) method

Belirtilen değeri sağ taraf argümanı olarak kullanarak, mevcut nesne tarafından temsil edilen değere [operator-=()](./) uygular.

```cpp
template<typename T1,typename> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator-=(const T1 &other)
```

### Template parameters

| Parametre | Açıklama |
| --- | --- |
| T1 | [operator-=()](./)'in sağ taraf değeri olarak kullanılan değerin tipi |

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const T1\& | Mevcut nesne tarafından temsil edilen değere uygulanan [operator-=()](./)'in sağ taraf değeri olarak kullanılan değerin sabit referansı. |

### Return Value

Kendisine bir referans

## Nullable::operator-=(const Nullable\<T1\>\&) method

Belirtilen [Nullable](../) nesnesi tarafından temsil edilen değeri sağ taraf argümanı olarak kullanarak, mevcut nesne tarafından temsil edilen değere [operator-=()](./) uygular.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator-=(const Nullable<T1> &other)
```

### Template parameters

| Parametre | Açıklama |
| --- | --- |
| T1 | [operator-=()](./)'in sağ taraf argümanı olarak kullanılan değerin temsil edildiği [Nullable](../) nesnesinin temel tipi |

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Mevcut nesne tarafından temsil edilen değere uygulanan [operator-=()](./)'nın sağ taraf argümanı olarak kullanılan [Nullable](../) nesnesinin sabit referansı. |

### Return Value

Kendisine bir referans

## See Also

* Class [Nullable](../)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)