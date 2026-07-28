---
title: BasicSystemIStreamWrapper
second_title: Aspose.Slides C++ API referencia
description: "A std::istream-szerű csomagoló, amely a BasicSystemIOStreamBuf-ot használja belső pufferként."
type: docs
weight: 66
url: /hu/system.io/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper osztály


A std::istream-szerű csomagoló, amely [BasicSystemIOStreamBuf](../basicsystemiostreambuf/)-t használ belső pufferként.

```cpp
template<typename Elem,typename Traits>class BasicSystemIStreamWrapper : public std::basic_istream<Elem, std::char_traits<Elem>>
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIStreamWrapper](./)\&&) | A move konstruktorban és a move hozzárendelő operátorban használatos, hogy visszaállítsa a mutatókat és meghívja a [swap()](./swap/)-t. |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Új példányt hoz létre a [BasicSystemIStreamWrapper](./)-ból. |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(const [BasicSystemIStreamWrapper](./)\&) | Másoló konstruktor. Törölve. |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([BasicSystemIStreamWrapper](./)\&&) | Move konstruktor. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIStreamWrapper](./)\&) | Másoló hozzárendelő operátor. Törölve. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIStreamWrapper](./)\&&) | Move hozzárendelő operátor. |
| void [swap](./swap/)([BasicSystemIStreamWrapper](./)\&) | A *this és **right** cseréjét hívja meg, ha nem egyenlőek. |
## Typedefek

| Typedef | Leírás |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |
## Lásd még

* Névtér [System::IO](../)
* Könyvtár [Aspose.Slides](../../)