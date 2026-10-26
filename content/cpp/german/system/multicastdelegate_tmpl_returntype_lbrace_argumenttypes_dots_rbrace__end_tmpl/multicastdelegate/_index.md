---
title: MulticastDelegate()
second_title: Aspose.Slides für C++ API-Referenz
description: Erzeugt eine leere Sammlung.
type: docs
weight: 1
url: /de/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/multicastdelegate/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate() Methode

Erzeugt eine leere Sammlung.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate()
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t) Methode

Entspricht dem Standardkonstruktor.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t)
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate\&) Methode

Führt eine flache Kopie der Delegatensammlung durch.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate &o)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| o | const MulticastDelegate\& | Eine Instanz der MulticastDelegate-Klasse, von der die Delegatensammlung kopiert wird. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate\&&) Methode

Verschiebekonstruktor.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate &&o) noexcept
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| o | MulticastDelegate\&& | Eine Instanz der MulticastDelegate-Klasse, von der die Delegatensammlung verschoben wird. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback\&&) Methode

Erzeugt eine Instanz und fügt den angegebenen Delegaten zur Delegatensammlung hinzu.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback &&initial)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| initial | [Callback](../callback/)\&& | Ein Delegat, der zur Delegatensammlung hinzugefügt wird. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(T) Methode

Erzeugt eine Instanz und fügt den angegebenen Wert zur Delegatensammlung hinzu.

```cpp
template<class T,typename> System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(T arg)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ des Werts, der zur Delegatensammlung der neu erstellten Instanz hinzugefügt werden soll; der Typ muss in den Callback-Typ konvertierbar sein. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg | T | Ein Wert, der zur Delegatensammlung hinzugefügt wird. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function\<ReturnType(ArgumentTypes...)>) Methode

Erzeugt eine Instanz und fügt den angegebenen Wert zur Delegatensammlung hinzu.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function<ReturnType(ArgumentTypes...)> arg)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg | std::function\<ReturnType(ArgumentTypes...)> | Ein Wert, der zur Delegatensammlung hinzugefügt wird. |

## Siehe auch

* Typedef [Callback](../callback/)
* Klasse [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)