---
title: Write()
second_title: Aspose.Slides för C++ API-referens
description: Skriver ut strängrepresentationen av det angivna objektet till standardutmatningsströmmen.
type: docs
weight: 1
url: /sv/system/console/write/
---
## Console::Write(const SharedPtr\<T\>\&) method

Skriver ut strängrepresentationen av det angivna objektet till standardutgångsströmmen.

```cpp
template<class T> static void System::Console::Write(const SharedPtr<T> &object)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ av objektet som ska skrivas ut |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| object | const [SharedPtr](../../sharedptr/)\<T\>\& | [Object](../../object/) att skriva ut |

## Console::Write(bool) method

Skriver ut strängrepresentationen av bool-värdet till standardutgångsströmmen.

```cpp
static void System::Console::Write(bool value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **bool** | Värdet som ska skrivas ut |

## Console::Write(char_t) method

Skriver ut det angivna teckenvärdet till standardutgångsströmmen.

```cpp
static void System::Console::Write(char_t value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char_t | Värdet som ska skrivas ut |

## Console::Write(const ArrayPtr\<char_t\>\&) method

Skriver ut strängrepresentationen av den angivna teckenarrayen till standardutgångsströmmen.

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Arrayen som ska skrivas ut |

## Console::Write(const Decimal\&) method

Skriver ut strängrepresentationen av [Decimal](../../decimal/)-värdet till standardutgångsströmmen.

```cpp
static void System::Console::Write(const Decimal &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | Värdet som ska skrivas ut |

## Console::Write(double) method

Skriver ut strängrepresentationen av double-precisions-flyttal till standardutgångsströmmen.

```cpp
static void System::Console::Write(double value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **double** | Värdet som ska skrivas ut |

## Console::Write(float) method

Skriver ut strängrepresentationen av float-precisions-flyttal till standardutgångsströmmen.

```cpp
static void System::Console::Write(float value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **float** | Värdet som ska skrivas ut |

## Console::Write(int32_t) method

Skriver ut strängrepresentationen av 32-bitars heltal till standardutgångsströmmen.

```cpp
static void System::Console::Write(int32_t value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **int32_t** | Värdet som ska skrivas ut |

## Console::Write(int64_t) method

Skriver ut strängrepresentationen av 64-bitars heltal till standardutgångsströmmen.

```cpp
static void System::Console::Write(int64_t value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **int64_t** | Värdet som ska skrivas ut |

## Console::Write(const String\&) method

Skriver ut det angivna strängobjektet till standardutgångsströmmen.

```cpp
static void System::Console::Write(const String &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängobjektet som ska skrivas ut |

## Console::Write(const char_t *) method

Skriver ut den angivna c-strängen till standardutgångsströmmen.

```cpp
static void System::Console::Write(const char_t *value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const char_t * | C-strängen som ska skrivas ut |

## Console::Write(const TypeInfo\&) method

Skriver ut strängrepresentationen av [TypeInfo](../../typeinfo/)-värdet till standardutgångsströmmen.

```cpp
static void System::Console::Write(const TypeInfo &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | Värdet som ska skrivas ut |

## Console::Write(uint32_t) method

Skriver ut strängrepresentationen av unsigned 32-bitars heltal till standardutgångsströmmen.

```cpp
static void System::Console::Write(uint32_t value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **uint32_t** | Värdet som ska skrivas ut |

## Console::Write(uint64_t) method

Skriver ut strängrepresentationen av unsigned 64-bitars heltal till standardutgångsströmmen.

```cpp
static void System::Console::Write(uint64_t value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **uint64_t** | Värdet som ska skrivas ut |

## Console::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) method

Skriver ut strängrepresentationen av det angivna intervallet av den specificerade teckenarrayen till standardutgångsströmmen.

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Teckenarrayen |
| index | **int32_t** | Indexet i arrayen där intervallet att skriva ut börjar |
| count | **int32_t** | Antalet element i intervallet att skriva ut |

## Console::Write(const String\&, Args\&&...) method

Skriver ut strängrepresentationen av de angivna argumenten formaterade enligt det angivna formatet till standardutgångsströmmen.

```cpp
template<class...> static void System::Console::Write(const String &format, Args &&... args)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| The | typerna av värdena som ska skrivas ut |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | const [String](../../string/)\& | Strängformatet |
| args | Args\&&... | Värdena som ska skrivas ut |

## Console::Write(const char *) method




```cpp
static void System::Console::Write(const char *)=delete
```

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Klass [Console](../)
* Klass [Decimal](../../decimal/)
* Klass [String](../../string/)
* Klass [TypeInfo](../../typeinfo/)
* Namnrymd [System](../../)
* Library [Aspose.Slides](../../../)