---
title: Format()
second_title: Aspose.Slides için C++ API Referansı
description: Dizeyi C# stilinde biçimlendirir.
type: docs
weight: 885
url: /tr/system/string/format/
---
## String::Format(const SharedPtr\<IFormatProvider\>\&, const String\&, const Args\&...) yöntemi

Dizeyi C# stilinde biçimlendirir.

```cpp
template<class...> String System::String::Format(const SharedPtr<IFormatProvider> &fp, const String &format, const Args &... args)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Args | Biçim dizesi için argümanlar. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Argümanları dizgelere dönüştürmek için kullanılacak biçim sağlayıcı. |
| format | const [String](../)\& | Biçim dizesi. |
| args | const Args\&... | Biçim dizesi için argümanlar. |

## String::Format(std::nullptr_t, const String\&, const Args\&...) yöntemi

Dizeyi C# stilinde biçimlendirir.

```cpp
template<class...> String System::String::Format(std::nullptr_t, const String &format, const Args &... args)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Args | Biçim dizesi için argümanlar. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| format | std::nullptr_t | Biçim dizesi. |
| args | const [String](../)\& | Biçim dizesi için argümanlar. |

## String::Format(std::nullptr_t, const char16_t(&), const Args\&...) yöntemi

Dizeyi C# stilinde biçimlendirir.

```cpp
template<std::size_t,class...> String System::String::Format(std::nullptr_t, const char16_t(&format)[N], const Args &... args)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Args | Biçim dizesi için argümanlar. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| format | std::nullptr_t | Biçim dizesi. |
| args | const char16_t(&) | Biçim dizesi için argümanlar. |

## String::Format(const String\&, const Args\&...) yöntemi

Dizeyi C# stilinde biçimlendirir.

```cpp
template<class...> String System::String::Format(const String &format, const Args &... args)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Args | Biçim dizesi için argümanlar. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| format | const [String](../)\& | Biçim dizesi. |
| args | const Args\&... | Biçim dizesi için argümanlar. |

## String::Format(const String\&, const System::ArrayPtr\<T\>\&) yöntemi

Dizeyi C# stilinde biçimlendirir.

```cpp
template<class T> String System::String::Format(const String &format, const System::ArrayPtr<T> &args)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Biçim dizesi için argümanlar. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| format | const [String](../)\& | Biçim dizesi. |
| args | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | Biçim dizesi için argümanlar. |

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../sharedptr/)
* Tip Tanımı [ArrayPtr](../../arrayptr/)
* Sınıf [String](../)
* Sınıf [IFormatProvider](../../iformatprovider/)
* İsim Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)