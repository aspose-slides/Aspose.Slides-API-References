---
title: Integral()
second_title: Aspose.Slides για C++ API Αναφορά
description: Παίρνει το ολοκλήρωμα
type: docs
weight: 196
url: /el/aspose.slides.mathtext/imathelement/integral/
---
## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) μέθοδος


Παίρνει το ολοκλήρωμα

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Τύπος ολοκληρώματος |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Κάτω όριο του ολοκληρώματος |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Άνω όριο του ολοκληρώματος |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | Τοποθεσία των ορίων |

### Τιμή επιστροφής

Νέα παρουσία τύπου [IMathNaryOperator](../../imathnaryoperator/)
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) μέθοδος


Παίρνει το ολοκλήρωμα

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Τύπος ολοκληρώματος |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Κάτω όριο του ολοκληρώματος |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Άνω όριο του ολοκληρώματος |

### Τιμή επιστροφής

Νέα παρουσία τύπου [IMathNaryOperator](../../imathnaryoperator/)
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes) μέθοδος


Παίρνει το ολοκλήρωμα χωρίς όρια

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Τύπος ολοκληρώματος |

### Τιμή επιστροφής

Νέα παρουσία τύπου [IMathNaryOperator](../../imathnaryoperator/)
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Contour);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) μέθοδος


Παίρνει το ολοκλήρωμα

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Τύπος ολοκληρώματος |
| lowerLimit | [System::String](../../../system/string/) | Κάτω όριο του ολοκληρώματος |
| upperLimit | [System::String](../../../system/string/) | Άνω όριο του ολοκληρώματος |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | Τοποθεσία των ορίων |

### Τιμή επιστροφής

Νέα παρουσία τύπου [IMathNaryOperator](../../imathnaryoperator/)
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String) μέθοδος


Παίρνει το ολοκλήρωμα

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Τύπος ολοκληρώματος |
| lowerLimit | [System::String](../../../system/string/) | Κάτω όριο του ολοκληρώματος |
| upperLimit | [System::String](../../../system/string/) | Άνω όριο του ολοκληρώματος |

### Τιμή επιστροφής

Νέα παρουσία τύπου [IMathNaryOperator](../../imathnaryoperator/)
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5");
```

## Δείτε επίσης

* Enum [MathIntegralTypes](../../mathintegraltypes/)
* Enum [MathLimitLocations](../../mathlimitlocations/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathNaryOperator](../../imathnaryoperator/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)