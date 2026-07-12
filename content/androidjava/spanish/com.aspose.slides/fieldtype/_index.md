---
title: FieldType
second_title: Referencia de API de Aspose.Slides para Android mediante Java
description: Representa un tipo de campo.
type: docs
url: /es/com.aspose.slides/fieldtype/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IFieldType](../../com.aspose.slides/ifieldtype)
```
public final class FieldType implements IFieldType
```

Representa un tipo de campo. Este valor determina qué texto se establecerá en la porción del campo cuando se actualice.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [FieldType(String str)](#FieldType-java.lang.String-) | Inicializa una nueva instancia de la clase FieldType. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getInternalString()](#getInternalString--) | Devuelve el nombre interno de este objeto FieldType. |
| [setInternalString(String value)](#setInternalString-java.lang.String-) | Devuelve el nombre interno de este objeto FieldType. |
| [equals(Object obj)](#equals-java.lang.Object-) | Comprueba si este campo es igual a otro. |
| [hashCode()](#hashCode--) | Devuelve el hashcode de este objeto. |
| [op_Equality(FieldType a, FieldType b)](#op-Equality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-) | Comprueba si dos objetos FieldType son iguales. |
| [op_Inequality(FieldType a, FieldType b)](#op-Inequality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-) | Comprueba si dos objetos FieldType no son iguales. |
| [getSlideNumber()](#getSlideNumber--) | Número de la diapositiva actual. |
| [getFooter()](#getFooter--) | Pie de página de la diapositiva. |
| [getHeader()](#getHeader--) | Encabezado de la diapositiva. |
| [getDateTime()](#getDateTime--) | Fecha y hora actuales en el formato de fecha y hora predeterminado de la aplicación de renderizado. |
| [getDateTime1()](#getDateTime1--) | Fecha y hora actuales en el primer formato predefinido (MM/DD/YYYY para inglés). |
| [getDateTime2()](#getDateTime2--) | Fecha y hora actuales en el segundo formato predefinido (Day, Month DD, YYYY para inglés). |
| [getDateTime3()](#getDateTime3--) | Fecha y hora actuales en el tercer formato predefinido (DD Month YYYY para inglés). |
| [getDateTime4()](#getDateTime4--) | Fecha y hora actuales en el cuarto formato predefinido (Month DD, YYYY para inglés). |
| [getDateTime5()](#getDateTime5--) | Fecha y hora actuales en el quinto formato predefinido (DD-Mon-YY para inglés). |
| [getDateTime6()](#getDateTime6--) | Fecha y hora actuales en el sexto formato predefinido (Month YY para inglés). |
| [getDateTime7()](#getDateTime7--) | Fecha y hora actuales en el séptimo formato predefinido (Mon-YY para inglés). |
| [getDateTime8()](#getDateTime8--) | Fecha y hora actuales en el octavo formato predefinido (MM/DD/YYYY hh:mm AM/PM para inglés). |
| [getDateTime9()](#getDateTime9--) | Fecha y hora actuales en el noveno formato predefinido (MM/DD/YYYY hh:mm:ss AM/PM para inglés). |
| [getDateTime10()](#getDateTime10--) | Fecha y hora actuales en el décimo formato predefinido (hh:mm para inglés). |
| [getDateTime11()](#getDateTime11--) | Fecha y hora actuales en el undécimo formato predefinido (hh:mm:ss para inglés). |
| [getDateTime12()](#getDateTime12--) | Fecha y hora actuales en el duodécimo formato predefinido (hh:mm AM/PM para inglés). |
| [getDateTime13()](#getDateTime13--) | Fecha y hora actuales en el decimotercer formato predefinido (hh:mm:ss AM/PM para inglés). |

### FieldType(String str) {#FieldType-java.lang.String-}
```
public FieldType(String str)
```

Inicializa una nueva instancia de la clase FieldType.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | java.lang.String |  |

### getInternalString() {#getInternalString--}
```
public final String getInternalString()
```

Devuelve el nombre interno de este objeto FieldType. Lectura/escritura String.

**Devuelve:**
java.lang.String

### setInternalString(String value) {#setInternalString-java.lang.String-}
```
public final void setInternalString(String value)
```

Devuelve el nombre interno de este objeto FieldType. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Comprueba si este campo es igual a otro.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | Campo a comparar. |

**Devuelve:**
boolean - Verdadero si los campos son iguales.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Devuelve el hashcode de este objeto.

**Devuelve:**
int - Hashcode int.

### op_Equality(FieldType a, FieldType b) {#op-Equality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-}
```
public static boolean op_Equality(FieldType a, FieldType b)
```

Comprueba si dos objetos FieldType son iguales.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [FieldType](../../com.aspose.slides/fieldtype) | Primer FieldType a comparar. |
| b | [FieldType](../../com.aspose.slides/fieldtype) | Segundo FieldType a comparar. |

**Devuelve:**
boolean - Verdadero si los objetos FieldType son iguales.

### op_Inequality(FieldType a, FieldType b) {#op-Inequality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-}
```
public static boolean op_Inequality(FieldType a, FieldType b)
```

Comprueba si dos objetos FieldType no son iguales.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [FieldType](../../com.aspose.slides/fieldtype) | Primer FieldType a comparar. |
| b | [FieldType](../../com.aspose.slides/fieldtype) | Segundo FieldType a comparar. |

**Devuelve:**
boolean - Verdadero si los objetos FieldType no son iguales.

### getSlideNumber() {#getSlideNumber--}
```
public static FieldType getSlideNumber()
```

Número de la diapositiva actual. Solo lectura [FieldType](../../com.aspose.slides/fieldtype).

**Devuelve:**
[FieldType](../../com.aspose.slides/fieldtype)

### getFooter() {#getFooter--}
```
public static FieldType getFooter()
```

Pie de página de la diapositiva. Solo lectura [FieldType](../../com.aspose.slides/fieldtype).

**Devuelve:**
[FieldType](../../com.aspose.slides/fieldtype)

### getHeader() {#getHeader--}
```
public static FieldType getHeader()
```

Encabezado de la diapositiva. Solo lectura [FieldType](../../com.aspose.slides/fieldtype).

**Devuelve:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime() {#getDateTime--}
```
public static FieldType getDateTime()
```

Fecha y hora actuales en el formato de fecha y hora predeterminado de la aplicación de renderizado. Solo lectura [FieldType](../../com.aspose.slides/fieldtype).

**Devuelve:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime1() {#getDateTime1--}
```
public static FieldType getDateTime1()
```

Fecha y hora actuales en el primer formato predefinido (MM/DD/YYYY para inglés). Solo lectura [FieldType](../../com.aspose.slides/fieldtype).

**Devuelve:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime2() {#getDateTime2--}
```
public static FieldType getDateTime2()
```

Fecha y hora actuales en el segundo formato predefinido (Day, Month DD, YYYY para inglés). Solo lectura [FieldType](../../com.aspose.slides/fieldtype).

**Devuelve:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime3() {#getDateTime3--}
```
public static FieldType getDateTime3()
```

Fecha y hora actuales en el tercer formato predefinido (DD Month YYYY para inglés). Solo lectura [FieldType](../../com.aspose.slides/fieldtype).

**Devuelve:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime4() {#getDateTime4--}
```
public static FieldType getDateTime4()
```

Fecha y hora actuales en el cuarto formato predefinido (Month DD, YYYY para inglés). Solo lectura [FieldType](../../com.aspose.slides/fieldtype).

**Devuelve:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime5() {#getDateTime5--}
```
public static FieldType getDateTime5()
```

Fecha y hora actuales en el quinto formato predefinido (DD-Mon-YY para inglés). Solo lectura [FieldType](../../com.aspose.slides/fieldtype).

**Devuelve:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime6() {#getDateTime6--}
```
public static FieldType getDateTime6()
```

Fecha y hora actuales en el sexto formato predefinido (Month YY para inglés). Solo lectura [FieldType](../../com.aspose.slides/fieldtype).

**Devuelve:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime7() {#getDateTime7--}
```
public static FieldType getDateTime7()
```

Fecha y hora actuales en el séptimo formato predefinido (Mon-YY para inglés). Solo lectura [FieldType](../../com.aspose.slides/fieldtype).

**Devuelve:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime8() {#getDateTime8--}
```
public static FieldType getDateTime8()
```

Fecha y hora actuales en el octavo formato predefinido (MM/DD/YYYY hh:mm AM/PM para inglés). Solo lectura [FieldType](../../com.aspose.slides/fieldtype).

**Devuelve:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime9() {#getDateTime9--}
```
public static FieldType getDateTime9()
```

Fecha y hora actuales en el noveno formato predefinido (MM/DD/YYYY hh:mm:ss AM/PM para inglés). Solo lectura [FieldType](../../com.aspose.slides/fieldtype).

**Devuelve:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime10() {#getDateTime10--}
```
public static FieldType getDateTime10()
```

Fecha y hora actuales en el décimo formato predefinido (hh:mm para inglés). Solo lectura [FieldType](../../com.aspose.slides/fieldtype).

**Devuelve:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime11() {#getDateTime11--}
```
public static FieldType getDateTime11()
```

Fecha y hora actuales en el undécimo formato predefinido (hh:mm:ss para inglés). Solo lectura [FieldType](../../com.aspose.slides/fieldtype).

**Devuelve:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime12() {#getDateTime12--}
```
public static FieldFormat getDateTime12()
```

Fecha y hora actuales en el duodécimo formato predefinido (hh:mm AM/PM para inglés). Solo lectura [FieldType](../../com.aspose.slides/fieldtype).

**Devuelve:**
[FieldType](../../com.aspose.slides/fieldtype)

### getDateTime13() {#getDateTime13--}
```
public static FieldType getDateTime13()
```

Fecha y hora actuales en el decimotercer formato predefinido (hh:mm:ss AM/PM para inglés). Solo lectura [FieldType](../../com.aspose.slides/fieldtype).

**Devuelve:**
[FieldType](../../com.aspose.slides/fieldtype)