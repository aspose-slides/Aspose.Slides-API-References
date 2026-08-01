---
title: GetHashCode()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een hashcode voor de opgegeven scalare waarde.
type: docs
weight: 2484
url: /nl/system/gethashcode/
---
## System::GetHashCode(const T\&) functie

Retourneert een hashcode voor de opgegeven scalare waarde.

```cpp
template<typename T> std::enable_if<std::is_scalar<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van de waarde waarvoor de functie een hashcode genereert |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const T\& | De waarde waarvoor een hashcode moet worden gegenereerd |

### Retourwaarde

De gegenereerde hashcode voor de opgegeven waarde

## System::GetHashCode(const T\&) functie

Retourneert een hashcode voor het opgegeven object.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&System::IsSmartPtr<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van het object waarvoor de functie een hashcode genereert |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const T\& | De [SmartPtr](../smartptr/) die naar het object wijst waarvoor een hashcode moet worden gegenereerd |

### Retourwaarde

De gegenereerde hashcode voor het opgegeven object

## System::GetHashCode(const T\&) functie

Retourneert een hashcode voor het opgegeven object dat een uitzondering is.

```cpp
template<typename T> std::enable_if<System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van het object waarvoor de functie een hashcode genereert |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const T\& | De Exception Wrapper die het object bevat waarvoor een hashcode moet worden gegenereerd |

### Retourwaarde

De gegenereerde hashcode voor het opgegeven object

## System::GetHashCode(const T\&) functie

Retourneert een hashcode voor het opgegeven object dat geen smart pointer of uitzondering is.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&!System::IsSmartPtr<T>::value &&!System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van het object waarvoor de functie een hashcode genereert |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const T\& | Een const-referentie naar het object waarvoor een hashcode moet worden gegenereerd |

### Retourwaarde

De gegenereerde hashcode voor het opgegeven object

## System::GetHashCode(const std::thread::id\&) functie

Specialisatie voor std::thread::id; retourneert de hashcode voor het opgegeven thread-object.

```cpp
int System::GetHashCode(const std::thread::id &id)
```

## Zie ook

* Struct [IsSmartPtr](../issmartptr/)
* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)