---
title: connect()
second_title: Aspose.Slides C++ API Referencia
description: Hozzáadja a megadott delegált a gyűjteményhez.
type: docs
weight: 144
url: /hu/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/connect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(Callback) metódus


Hozzáadja a megadott delegált a gyűjteményhez.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(Callback callback)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| callback | [Callback](../callback/) | A delegáta, amelyet a gyűjteményhez adunk hozzá |

### Visszatérési érték

Az önre mutató referencia

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(std::function\<R(Args...)>) metódus


Hozzáadja a megadott függvényobjektumot a delegált gyűjteményhez. A függvényobjektum a delegált gyűjteményhez adás előtt a Callback delegáta típusra konvertálódik.

```cpp
template<class R,class...> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(std::function<R(Args...)> f)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| R | A függvényobjektum visszatérési típusa, amelyet a gyűjteményhez adunk hozzá |
| Args | A függvényobjektum argumentumlistája, amelyet a gyűjteményhez adunk hozzá |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| f | std::function\<R(Args...)> | A függvényobjektum, amelyet a gyűjteményhez adunk hozzá |

### Visszatérési érték

Az önre mutató referencia

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MulticastDelegate\&) metódus


Hozzáadja a megadott MulticastDelegate objektumot a delegált gyűjteményhez.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MulticastDelegate &other)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | A MulticastDelegate osztály egy példánya, amelyet a delegált gyűjteményhez adunk hozzá |

### Visszatérési érték

Az önre mutató referencia

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, ClassType *) metódus


Hozzáadja a megadott objektum nem statikus metódusát a delegált gyűjteményhez.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, ClassType *obj)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| MemberType | A nem statikus metódus típusa, amelyet a delegált gyűjteményhez adunk hozzá |
| ClassType | Az objektum típusa, amelynek a metódusát a delegált gyűjteményhez adunk hozzá |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| member | MemberType ClassType::* | A megadott objektum nem statikus metódusára mutató pointer |
| obj | ClassType * | Az objektum egy tagmetódusára mutató pointer, amelyet a delegált gyűjteményhez adunk hozzá |

### Visszatérési érték

Az önre mutató referencia

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) metódus


Hozzáadja a megadott objektum nem statikus metódusát a delegált gyűjteményhez.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| MemberType | A nem statikus metódus típusa, amelyet a delegált gyűjteményhez adunk hozzá |
| ClassType | Az objektum típusa, amelynek a metódusa a delegált gyűjteményhez kerül hozzáadásra |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| member | MemberType ClassType::* | A megadott objektum nem statikus metódusára mutató pointer |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Egy megosztott mutató az objektum tagmetódusára, amelyet a delegált gyűjteményhez adunk hozzá |

### Visszatérési érték

Az önre mutató referencia

## Lásd még

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Metódus [MulticastDelegate](../multicastdelegate/)
* Osztály [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)