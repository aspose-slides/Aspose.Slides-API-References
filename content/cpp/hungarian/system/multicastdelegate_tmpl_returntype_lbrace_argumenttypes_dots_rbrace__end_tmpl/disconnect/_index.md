---
title: disconnect()
second_title: Aspose.Slides for C++ API referencia
description: Eltávolítja a megadott delegált a delegáló gyűjteményből.
type: docs
weight: 170
url: /hu/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/disconnect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(Callback) method

Eltávolítja a megadott delegált a delegáló gyűjteményből.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(Callback callback)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| callback | [Callback](../callback/) | A delegát, amelyet el kell távolítani a gyűjteményből |

### Visszatérési érték

Az objektumra mutató referencia

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, ClassType *) method

Eltávolítja a megadott nem statikus metódust a megadott objektumtól a delegáló gyűjteményből.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, ClassType *obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| MemberType | A nem statikus metódus típusa, amelyet el kell távolítani a delegáló gyűjteményből |
| ClassType | Az objektum típusa, amelynek a metódusát el kell távolítani a delegáló gyűjteményből |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- --- | --- | --- |
| member | MemberType ClassType::* | A megadott objektum nem statikus metódusára mutató pointer |
| obj | ClassType * | Egy objektumra mutató pointer, amelynek a tagmetódusát el kell távolítani a delegáló gyűjteményből |

### Visszatérési érték

Az objektumra mutató referencia

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) method

Eltávolítja a megadott nem statikus metódust a megadott objektumtól a delegáló gyűjteményből.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| MemberType | A nem statikus metódus típusa, amelyet el kell távolítani a delegáló gyűjteményből |
| ClassType | Az objektum típusa, amelynek a metódusát el kell távolítani a delegáló gyűjteményből |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| member | MemberType ClassType::* | A megadott objektum nem statikus metódusára mutató pointer |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | A megadott objektum tagmetódusára mutató megosztott mutató, amelyet el kell távolítani a delegáló gyűjteményből |

### Visszatérési érték

Az objektumra mutató referencia

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate\&) method

Eltávolítja a megadott MulticastDelegate objektumot a delegáló gyűjteményből.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate &other)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | A MulticastDelegate osztály egy példánya, amelyet el kell távolítani a delegáló gyűjteményből |

### Visszatérési érték

Az objektumra mutató referencia

## Lásd még

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Metódus [MulticastDelegate](../multicastdelegate/)
* Osztály [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)