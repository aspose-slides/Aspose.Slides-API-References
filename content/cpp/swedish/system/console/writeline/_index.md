---
title: WriteLine()
second_title: Aspose.Slides för C++ API-referens
description: Skriver ut den aktuella radslutstecknet till standardutgångsströmmen.
type: docs
weight: 14
url: /sv/system/console/writeline/
---
## Console::WriteLine() metod

Skriver ut den aktuella radslutstecknet till standardutgångsströmmen.

```cpp
static void System::Console::WriteLine()
```

## Console::WriteLine(const SharedPtr\<T\>\&) metod

Skriver ut objektets strängrepresentation följt av det aktuella radslutstecknet till standardutgångsströmmen.

```cpp
template<class T> static void System::Console::WriteLine(const SharedPtr<T> &object)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på objektet som ska skrivas ut |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| object | const [SharedPtr](../../sharedptr/)\<T\>\& | [Object](../../object/) att skriva ut |

## Console::WriteLine(bool) metod

Skriver ut bool-värdets strängrepresentation följt av det aktuella radslutstecknet till standardutgångsströmmen.

```cpp
static void System::Console::WriteLine(bool value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **bool** | Värdet som ska skrivas ut |

## Console::WriteLine(char_t) metod

Skriver ut det angivna teckenvärdet följt av det aktuella radslutstecknet till standardutgångsströmmen.

```cpp
static void System::Console::WriteLine(char_t value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char_t | Värdet som ska skrivas ut |

## Console::WriteLine(const ArrayPtr\<char_t\>\&) metod

Skriver ut den angivna teckenarrayens strängrepresentation följt av det aktuella radslutstecknet till standardutgångsströmmen.

```cpp
static void System::Console::WriteLine(const ArrayPtr<char_t> &buffer)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Arrayen som ska skrivas ut |

## Console::WriteLine(const Decimal\&) metod

Skriver ut [Decimal](../../decimal/)-värdets strängrepresentation följt av det aktuella radslutstecknet till standardutgångsströmmen.

```cpp
static void System::Console::WriteLine(const Decimal &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | Värdet som ska skrivas ut |

## Console::WriteLine(double) metod

Skriver ut den dubbelprecision-flyttalets strängrepresentation följt av det aktuella radslutstecknet till standardutgångsströmmen.

```cpp
static void System::Console::WriteLine(double value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **double** | Värdet som ska skrivas ut |

## Console::WriteLine(float) metod

Skriver ut den enkelprecisions-flyttalets strängrepresentation följt av det aktuella radslutstecknet till standardutgångsströmmen.

```cpp
static void System::Console::WriteLine(float value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **float** | Värdet som ska skrivas ut |

## Console::WriteLine(int32_t) metod

Skriver ut den 32-bitars heltalsvärdets strängrepresentation följt av det aktuella radslutstecknet till standardutgångsströmmen.

```cpp
static void System::Console::WriteLine(int32_t value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **int32_t** | Värdet som ska skrivas ut |

## Console::WriteLine(int64_t) metod

Skriver ut den 64-bitars heltalsvärdets strängrepresentation följt av det aktuella radslutstecknet till standardutgångsströmmen.

```cpp
static void System::Console::WriteLine(int64_t value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **int64_t** | Värdet som ska skrivas ut |

## Console::WriteLine(const String\&) metod

Skriver ut det angivna strängobjektet följt av det aktuella radslutstecknet till standardutgångsströmmen.

```cpp
static void System::Console::WriteLine(const String &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängobjektet som ska skrivas ut |

## Console::WriteLine(const char_t *) metod

Skriver ut den angivna c-strängen följt av det aktuella radslutstecknet till standardutgångsströmmen.

```cpp
static void System::Console::WriteLine(const char_t *value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const char_t * | c-strängen som ska skrivas ut |

## Console::WriteLine(const TypeInfo\&) metod

Skriver ut [TypeInfo](../../typeinfo/)-värdets strängrepresentation följt av det aktuella radslutstecknet till standardutgångsströmmen.

```cpp
static void System::Console::WriteLine(const TypeInfo &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | Värdet som ska skrivas ut |

## Console::WriteLine(uint32_t) metod

Skriver ut den 32-bitars osignerade heltalsvärdets strängrepresentation följt av det aktuella radslutstecknet till standardutgångsströmmen.

```cpp
static void System::Console::WriteLine(uint32_t value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **uint32_t** | Värdet som ska skrivas ut |

## Console::WriteLine(uint64_t) metod

Skriver ut den 64-bitars osignerade heltalsvärdets strängrepresentation följt av det aktuella radslutstecknet till standardutgångsströmmen.

```cpp
static void System::Console::WriteLine(uint64_t value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **uint64_t** | Värdet som ska skrivas ut |

## Console::WriteLine(const ArrayPtr\<char_t\>\&, int, int) metod

Skriver ut strängrepresentationen av det angivna intervallet i den angivna teckenarrayen följt av det aktuella radslutstecknet till standardutgångsströmmen.

```cpp
static void System::Console::WriteLine(const ArrayPtr<char_t> &buffer, int index, int count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Teckenarrayen |
| index | int | Indexet i arrayen där intervallet att skriva ut börjar |
| count | int | Antalet element i intervallet som ska skrivas ut |

## Console::WriteLine(const Exception\&) metod

Skriver ut strängrepresentationen av det angivna Exception-objektet följt av det aktuella radslutstecknet till standardutgångsströmmen.

```cpp
static void System::Console::WriteLine(const Exception &e)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| e | const [Exception](../../exception/)\& | Värdet som ska skrivas ut |

## Console::WriteLine(const String\&, Args\&&...) metod

Skriver ut strängrepresentationen av de angivna argumenten formaterade enligt det angivna formatet följt av det aktuella radslutstecknet till standardutgångsströmmen.

```cpp
template<class...> static void System::Console::WriteLine(const String &format, Args &&... args)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| The | typerna på värdena som ska skrivas ut |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | const [String](../../string/)\& | Strängformatet |
| args | Args\&&... | Värdena som ska skrivas ut |

## Console::WriteLine(const char *) metod




```cpp
static void System::Console::WriteLine(const char *)=delete
```

## Se också

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Exception](../../exception/)
* Class [Console](../)
* Class [Decimal](../../decimal/)
* Class [String](../../string/)
* Class [TypeInfo](../../typeinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)