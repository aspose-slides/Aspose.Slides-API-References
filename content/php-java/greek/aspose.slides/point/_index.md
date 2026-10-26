---
title: Point
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs
url: /el/aspose.slides/point/
---
## Κλάση Point

Αναπαριστά σημείο animation.

### Point {#Point}

| Όνομα | Περιγραφή |
| --- | --- |
| Point() | Προεπιλεγμένη μέθοδος. |

**Επιστρέφει:**
Point


---


### Point {#Point}

| Όνομα | Περιγραφή |
| --- | --- |
| Point(float, Object, String) | Δημιουργεί σημείο animation με χρόνο, τιμή και τύπο. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| time | float | Τιμή χρόνου. |
| value | Object | Τιμή σημείου. |
| formula | String | Τύπος. |

**Επιστρέφει:**
Point


---


### getFormula {#getFormula}

| Όνομα | Περιγραφή |
| --- | --- |
| getFormula () | Οι τύποι εντός των τιμών, των χαρακτηριστικών from, to, by μπορούν να αποτελούνται από τα εξής: Standard arithmetic operators: &#39+&#39, &#39-&#39, &#39*&#39, &#39/&#39, &#39^&#39, &#39%&#39 (mod) Constants: &#39pi&#39 &#39e&#39 Conditional operators: &#39abs&#39, &#39min&#39, &#39max&#39, &#39&#63&#39 (if) Comparison operators: &#39==&#39, &#39&gt;=&#39, &#39&#39, &#39&#33&#61&#39, &#39&#33&#39 Trigonometric operators: &#39sin()&#39, &#39cos()&#39, &#39tan()&#39, &#39asin()&#39, &#39acos()&#39, &#39atan()&#39 Natural logarithm &#39ln()&#39 Property references (host supported properties) for example: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" Read/write String. |

**Επιστρέφει:**
String


---


### getTime {#getTime}

| Όνομα | Περιγραφή |
| --- | --- |
| getTime () | Αντιπροσωπεύει την τιμή χρόνου. Read/write float. |

**Επιστρέφει:**
float


---


### getValue {#getValue}

| Όνομα | Περιγραφή |
| --- | --- |
| getValue () | Αντιπροσωπεύει την τιμή του σημείου. Only: bool, ColorFormat, float, int, string. Read/write Object. |

**Επιστρέφει:**
Object


---


### setFormula {#setFormula}

| Όνομα | Περιγραφή |
| --- | --- |
| setFormula (String) | Οι τύποι εντός των τιμών, των χαρακτηριστικών from, to, by μπορούν να αποτελούνται από τα εξής: Standard arithmetic operators: &#39+&#39, &#39-&#39, &#39*&#39, &#39/&#39, &#39^&#39, &#39%&#39 (mod) Constants: &#39pi&#39 &#39e&#39 Conditional operators: &#39abs&#39, &#39min&#39, &#39max&#39, &#39&#63&#39 (if) Comparison operators: &#39==&#39, &#39&gt;=&#39, &#39&#39, &#39&#33&#61&#39, &#39&#33&#39 Trigonometric operators: &#39sin()&#39, &#39cos()&#39, &#39tan()&#39, &#39asin()&#39, &#39acos()&#39, &#39atan()&#39 Natural logarithm &#39ln()&#39 Property references (host supported properties) for example: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" Read/write String. |

**Επιστρέφει:**
void


---


### setTime {#setTime}

| Όνομα | Περιγραφή |
| --- | --- |
| setTime (float) | Αντιπροσωπεύει την τιμή χρόνου. Read/write float. |

**Επιστρέφει:**
void


---


### setValue {#setValue}

| Όνομα | Περιγραφή |
| --- | --- |
| setValue (Object) | Αντιπροσωπεύει την τιμή του σημείου. Only: bool, ColorFormat, float, int, string. Read/write Object. |

**Επιστρέφει:**
void


---