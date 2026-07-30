---
title: ArrayInitializerCast()
second_title: Aspose.Slides pro C++ – reference API
description: Převádí základní hodnoty pole (což C# provádí implicitně, ale C++ zjevně ne).
type: docs
weight: 209
url: /cs/system/objectext/arrayinitializercast/
---
## ObjectExt::ArrayInitializerCast(From ...) metoda


Převádí základní hodnoty pole (což C# provádí implicitně, ale C++ zjevně ne).

```cpp
template<typename To,typename ...> static std::enable_if<(std::is_fundamental<To>::value), std::array<To, sizeof...(From)>>::type System::ObjectExt::ArrayInitializerCast(From ...args)
```


### Parametry šablony

| Parameter | Description |
| --- | --- |
| To | Target type. |
| From | Source types. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| args | From ... | Values to convert and push to target array. |

### Návratová hodnota

[Array](../../array/) obsahující převedené kopie všech argumentů ve stejném pořadí.

## Viz také

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)