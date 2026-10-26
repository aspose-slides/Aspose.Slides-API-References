---
title: BasicSystemOStreamWrapper
second_title: Aspose.Slides C++ API referencia
description: "Olyan std::ostream-szerű csomagolót képvisel, amely a BasicSystemIOStreamBuf-ot használja belső puffereként."
type: docs
weight: 79
url: /hu/system.io/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper osztály


Olyan std::ostream-szerű csomagoló, amely a [BasicSystemIOStreamBuf](../basicsystemiostreambuf/)-t használja belső pufferként.

```cpp
template<typename Elem,typename Traits>class BasicSystemOStreamWrapper : public std::basic_ostream<Elem, std::char_traits<Elem>>
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemOStreamWrapper](./)\&&) | Használják a mozgató konstruktorban és a mozgató hozzárendelő operátorban a pointerek visszaállításához és a [swap()](./swap/) meghívásához. |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Új példányt hoz létre a [BasicSystemOStreamWrapper](./)-ból. |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(const [BasicSystemOStreamWrapper](./)\&) | Másoló konstruktor. Törölve. |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([BasicSystemOStreamWrapper](./)\&&) | Mozgató konstruktor. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemOStreamWrapper](./)\&) | Másoló hozzárendelő operátor. Törölve. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemOStreamWrapper](./)\&&) | Mozgató hozzárendelő operátor. |
| void [swap](./swap/)([BasicSystemOStreamWrapper](./)\&) | Hívás a *this és **right** cseréjére, ha nem egyenlőek. |
## Typedefek

| Typedef | Leírás |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |
## Lásd még

* Névterület [System::IO](../)
* Könyvtár [Aspose.Slides](../../)