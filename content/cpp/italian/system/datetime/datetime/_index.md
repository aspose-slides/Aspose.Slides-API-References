---
title: DateTime()
second_title: Riferimento API Aspose.Slides per C++
description: Costruisce un'istanza che rappresenta il valore di data e ora più piccolo possibile, uguale a MinValue.
type: docs
weight: 1
url: /it/system/datetime/datetime/
---
## DateTime::DateTime() costruttore

Crea un'istanza che rappresenta il valore di data e ora più piccolo possibile, uguale a MinValue.

```cpp
constexpr System::DateTime::DateTime()
```

## DateTime::DateTime(int, int, int) costruttore

Crea un'istanza che rappresenta un valore di data e ora specificato come anno, mese e giorno particolari.

```cpp
System::DateTime::DateTime(int year, int month, int day)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| year | int | L'anno da rappresentare nell'istanza in costruzione. |
| month | int | Il mese dell'**year** da rappresentare nell'istanza in costruzione. |
| day | int | Il giorno del **month** da rappresentare nell'istanza in costruzione. |

## DateTime::DateTime(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) costruttore

Crea un'istanza che rappresenta un valore di data e ora specificato come anno, mese e giorno particolari nel calendario specificato.

```cpp
System::DateTime::DateTime(int year, int month, int day, const SharedPtr<Globalization::Calendar> &calendar)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| year | int | L'anno da rappresentare nell'istanza in costruzione. |
| month | int | Il mese dell'**year** da rappresentare nell'istanza in costruzione. |
| day | int | Il giorno del **month** da rappresentare nell'istanza in costruzione. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Il calendario usato per interpretare l'**year**, il **month** e il **day** specificati. |

## DateTime::DateTime(int, int, int, int, int, int) costruttore

Crea un'istanza che rappresenta un valore di data e ora specificato come anno, mese, giorno, ora, minuto e secondo particolari.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| year | int | L'anno da rappresentare nell'istanza in costruzione. |
| month | int | Il mese dell'**year** da rappresentare nell'istanza in costruzione. |
| day | int | Il giorno del **month** da rappresentare nell'istanza in costruzione. |
| hour | int | L'ora del **day** da rappresentare nell'istanza in costruzione. |
| minute | int | Il minuto dell'**hour** da rappresentare nell'istanza in costruzione. |
| second | int | Il secondo del **minute** da rappresentare nell'istanza in costruzione. |

## DateTime::DateTime(int, int, int, int, int, int, DateTimeKind) costruttore

Crea un'istanza che rappresenta un valore di data e ora specificato come anno, mese, giorno, ora, minuto e secondo particolari.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, DateTimeKind kind)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| year | int | L'anno da rappresentare nell'istanza in costruzione. |
| month | int | Il mese dell'**year** da rappresentare nell'istanza in costruzione. |
| day | int | Il giorno del **month** da rappresentare nell'istanza in costruzione. |
| hour | int | L'ora del **day** da rappresentare nell'istanza in costruzione. |
| minute | int | Il minuto dell'**hour** da rappresentare nell'istanza in costruzione. |
| second | int | Il secondo del **minute** da rappresentare nell'istanza in costruzione. |
| kind | [DateTimeKind](../../datetimekind/) | Il valore che indica se i parametri di data e ora forniti specificano un orario locale, UTC o nessuno dei due. |

## DateTime::DateTime(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) costruttore

Crea un'istanza che rappresenta un valore di data e ora specificato come anno, mese, giorno, ora, minuto e secondo particolari nel calendario specificato.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, const SharedPtr<Globalization::Calendar> &calendar)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| year | int | L'anno da rappresentare nell'istanza in costruzione. |
| month | int | Il mese dell'**year** da rappresentare nell'istanza in costruzione. |
| day | int | Il giorno del **month** da rappresentare nell'istanza in costruzione. |
| hour | int | L'ora del **day** da rappresentare nell'istanza in costruzione. |
| minute | int | Il minuto dell'**hour** da rappresentare nell'istanza in costruzione. |
| second | int | Il secondo del **minute** da rappresentare nell'istanza in costruzione. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Il calendario usato per interpretare l'**year**, il **month** e il **day** specificati. |

## DateTime::DateTime(int, int, int, int, int, int, int, DateTimeKind) costruttore

Crea un'istanza che rappresenta un valore di data e ora specificato come anno, mese, giorno, ora, minuto, secondo e millisecondo particolari.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, DateTimeKind kind=DateTimeKind::Unspecified)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| year | int | L'anno da rappresentare nell'istanza in costruzione. |
| month | int | Il mese dell'**year** da rappresentare nell'istanza in costruzione. |
| day | int | Il giorno del **month** da rappresentare nell'istanza in costruzione. |
| hour | int | L'ora del **day** da rappresentare nell'istanza in costruzione. |
| minute | int | Il minuto dell'**hour** da rappresentare nell'istanza in costruzione. |
| second | int | Il secondo del **minute** da rappresentare nell'istanza in costruzione. |
| millisecond | int | Il millisecondo del **second** da rappresentare nell'istanza in costruzione. |
| kind | [DateTimeKind](../../datetimekind/) | Il valore che indica se i parametri di data e ora forniti specificano un orario locale, UTC o nessuno dei due. |

## DateTime::DateTime(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) costruttore

Crea un'istanza che rappresenta un valore di data e ora specificato come anno, mese, giorno, ora, minuto, secondo e millisecondo particolari nel calendario specificato.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, DateTimeKind kind=DateTimeKind::Unspecified)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| year | int | L'anno da rappresentare nell'istanza in costruzione. |
| month | int | Il mese dell'**year** da rappresentare nell'istanza in costruzione. |
| day | int | Il giorno del **month** da rappresentare nell'istanza in costruzione. |
| hour | int | L'ora del **day** da rappresentare nell'istanza in costruzione. |
| minute | int | Il minuto dell'**hour** da rappresentare nell'istanza in costruzione. |
| second | int | Il secondo del **minute** da rappresentare nell'istanza in costruzione. |
| millisecond | int | Il millisecondo del **second** da rappresentare nell'istanza in costruzione. |
| kind | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Il valore che indica se i parametri di data e ora forniti specificano un orario locale, UTC o nessuno dei due. |
| calendar | [DateTimeKind](../../datetimekind/) | Il calendario usato per interpretare l'**year**, il **month** e il **day** specificati. |

## DateTime::DateTime(int64_t, DateTimeKind) costruttore

Crea un'istanza che rappresenta un valore di data e ora specificato come numero di tick.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind=DateTimeKind::Unspecified)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ticks | **int64_t** | Il numero di intervalli di 100 ns trascorsi dal 1 gennaio 0001 00:00:00.000 nel calendario georgiano. |
| kind | [DateTimeKind](../../datetimekind/) | Il valore che indica se il parametro **ticks** specifica un orario locale, UTC o nessuno dei due. |

## DateTime::DateTime(int64_t, DateTimeKind, bool) costruttore

Crea un'istanza che rappresenta un valore di data e ora specificato come numero di tick. PER USO INTERNO.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind, bool is_ambiguous_local_dst)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ticks | **int64_t** | Il numero di intervalli di 100 ns trascorsi dal 1 gennaio 0001 00:00:00.000 nel calendario georgiano. |
| kind | [DateTimeKind](../../datetimekind/) | Il valore che indica se il parametro **ticks** specifica un orario locale, UTC o nessuno dei due. |
| is_ambiguous_local_dst | **bool** | True se la data e ora specificate sono ambigue e possono essere mappate a molti orari UTC. |

## DateTime::DateTime(const DateTime\&) costruttore

Costruisce un'istanza copiandone un'altra.

```cpp
System::DateTime::DateTime(const DateTime &dt)=default
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dt | const [DateTime](../)\& | Un'istanza della classe [DateTime](../) da cui copiare il valore di data e ora rappresentato |

## Vedi anche

* Enum [DateTimeKind](../../datetimekind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../)
* Class [Calendar](../../../system.globalization/calendar/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)