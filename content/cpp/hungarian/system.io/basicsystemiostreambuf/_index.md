---
title: BasicSystemIOStreamBuf
second_title: Aspose.Slides for C++ API referenciája
description: "Olyan puffert képvisel, amely a System::IO::Stream-szerű adatfolyamokat csomagolja, és lehetővé teszi, hogy azokat std::iostream-szerű adatfolyamok belső puffereként használják."
type: docs
weight: 40
url: /hu/system.io/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf osztály

Egy puffert reprezentál, amely [System::IO::Stream](../stream/)-szerű adatfolyamokat csomagol, és lehetővé teszi, hogy azokat std::iostream-szerű adatfolyamok belső puffereként használják.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamBuf : public std::basic_streambuf<Elem, std::char_traits<Elem>>
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamBuf](./)\&&) | A move konstruktor és a move hozzárendelő operátor használja a mutatók visszaállításához és a [swap()](./swap/) meghívásához. |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)() | Új példányt hoz létre a [BasicSystemIOStreamBuf](./)-ból. |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/), const std::locale\&) | Új példányt hoz létre a [BasicSystemIOStreamBuf](./)-ból. |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [BasicSystemIOStreamBuf](./)\&) | Másoló konstruktor. Törölve. |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)([BasicSystemIOStreamBuf](./)\&&) | Move konstruktor. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamBuf](./)\&) | Másoló hozzárendelő operátor. Törölve. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamBuf](./)\&&) | Move hozzárendelő operátor. |
| void [swap](./swap/)([BasicSystemIOStreamBuf](./)\&) | *this és a right cseréje, ha nem egyenlőek. |
|  [~BasicSystemIOStreamBuf](./~basicsystemiostreambuf/)() override | Destruktor. |

## Typedefok

| Typedef | Leírás |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mysb](./mysb/) |  |
| [int_type](./int_type/) |  |
| [pos_type](./pos_type/) |  |
| [off_type](./off_type/) |  |

## Lásd még

* Névtere [System::IO](../)
* Könyvtár [Aspose.Slides](../../)