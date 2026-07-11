---
title: ColorTransformOperation
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Ορίζει λειτουργία μετασχηματισμού χρώματος.
type: docs
url: /el/com.aspose.slides/colortransformoperation/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorTransformOperation extends System.Enum
```

Ορίζει λειτουργία μετασχηματισμού χρώματος.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [Tint](#Tint) | Αποχρωματίζει το χρώμα. |
| [Shade](#Shade) | Σκιάζει το χρώμα. |
| [Complement](#Complement) | Αλλάζει το χρώμα σε RGB συμπληρωματικό. |
| [Inverse](#Inverse) | Αλλάζει το χρώμα σε αντιστροφή. |
| [Grayscale](#Grayscale) | Αλλάζει το χρώμα σε γκρι με την ίδια φωτεινότητα. |
| [SetAlpha](#SetAlpha) | Καθορίζει ένα άλφα συστατικό του χρώματος. |
| [AddAlpha](#AddAlpha) | Προσθέτει την τιμή μιας παραμέτρου σε ένα άλφα συστατικό του χρώματος. |
| [MultiplyAlpha](#MultiplyAlpha) | Πολλαπλασιάζει ένα άλφα συστατικό με την τιμή μιας παραμέτρου. |
| [SetHue](#SetHue) | Αλλάζει το συστατικό απόχρωσης του χρώματος στην τιμή μιας παραμέτρου. |
| [AddHue](#AddHue) | Προσθέτει την τιμή μιας παραμέτρου στο συστατικό απόχρωσης του χρώματος. |
| [MultiplyHue](#MultiplyHue) | Πολλαπλασιάζει το συστατικό απόχρωσης με την τιμή μιας παραμέτρου. |
| [SetSaturation](#SetSaturation) | Αλλάζει το συστατικό κορεσμού του χρώματος στην τιμή μιας παραμέτρου. |
| [AddSaturation](#AddSaturation) | Προσθέτει την τιμή μιας παραμέτρου στο συστατικό κορεσμού του χρώματος. |
| [MultiplySaturation](#MultiplySaturation) | Πολλαπλασιάζει το συστατικό κορεσμού με την τιμή μιας παραμέτρου. |
| [SetLuminance](#SetLuminance) | Αλλάζει το συστατικό φωτεινότητας του χρώματος στην τιμή μιας παραμέτρου. |
| [AddLuminance](#AddLuminance) | Προσθέτει την τιμή μιας παραμέτρου στο συστατικό φωτεινότητας του χρώματος. |
| [MultiplyLuminance](#MultiplyLuminance) | Πολλαπλασιάζει το συστατικό φωτεινότητας με την τιμή μιας παραμέτρου. |
| [SetRed](#SetRed) | Αλλάζει το κόκκινο συστατικό του χρώματος στην τιμή μιας παραμέτρου. |
| [AddRed](#AddRed) | Προσθέτει την τιμή μιας παραμέτρου στο κόκκινο συστατικό του χρώματος. |
| [MultiplyRed](#MultiplyRed) | Πολλαπλασιάζει το κόκκινο συστατικό με μια παράμετρο. |
| [SetGreen](#SetGreen) | Αλλάζει το πράσινο συστατικό του χρώματος στην τιμή μιας παραμέτρου. |
| [AddGreen](#AddGreen) | Προσθέτει μια παράμετρο στο πράσινο συστατικό του χρώματος. |
| [MultiplyGreen](#MultiplyGreen) | Πολλαπλασιάζει το πράσινο συστατικό του χρώματος με την τιμή μιας παραμέτρου. |
| [SetBlue](#SetBlue) | Αλλάζει το μπλε συστατικό του χρώματος στην τιμή μιας παραμέτρου. |
| [AddBlue](#AddBlue) | Προσθέτει την τιμή μιας παραμέτρου στο μπλε συστατικό του χρώματος. |
| [MultiplyBlue](#MultiplyBlue) | Πολλαπλασιάζει το μπλε συστατικό του χρώματος με την τιμή μιας παραμέτρου. |
| [Gamma](#Gamma) | Διόρθωση γάμμα. |
| [InverseGamma](#InverseGamma) | Αντίστροφη διόρθωση γάμμα. |
### Tint {#Tint}
```
public static final int Tint
```

Δίνει απόχρωση στο χρώμα. Η παράμετρος κυμαίνεται μεταξύ 0 (αρχικό χρώμα) και 1 (λευκό).

### Shade {#Shade}
```
public static final int Shade
```

Δίνει σκιά στο χρώμα. Η παράμετρος κυμαίνεται μεταξύ 0 (αρχικό χρώμα) και 1 (μαύρο).

### Complement {#Complement}
```
public static final int Complement
```

Αλλάζει το χρώμα σε RGB συμπληρωματικό. m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

### Inverse {#Inverse}
```
public static final int Inverse
```

Αλλάζει το χρώμα σε αντιστροφή. r = 1 - r; g = 1 - g; b = 1 - b;

### Grayscale {#Grayscale}
```
public static final int Grayscale
```

Αλλάζει το χρώμα σε γκρι με την ίδια φωτεινότητα. Η παράμετρος αγνοείται.

### SetAlpha {#SetAlpha}
```
public static final int SetAlpha
```

Καθορίζει ένα άλφα συστατικό του χρώματος. Η παράμετρος κυμαίνεται μεταξύ 0 (διαφανές) και 1 (αδιαφανές).

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```

Προσθέτει την τιμή μιας παραμέτρου σε ένα άλφα συστατικό του χρώματος. Η παράμετρος κυμαίνεται μεταξύ -1 και 1.

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

Πολλαπλασιάζει ένα άλφα συστατικό με την τιμή μιας παραμέτρου.

### SetHue {#SetHue}
```
public static final int SetHue
```

Αλλάζει το συστατικό απόχρωσης του χρώματος στην τιμή μιας παραμέτρου. Η παράμετρος κυμαίνεται μεταξύ 0 και 360.

### AddHue {#AddHue}
```
public static final int AddHue
```

Προσθέτει την τιμή μιας παραμέτρου στο συστατικό απόχρωσης του χρώματος. Η παράμετρος κυμαίνεται μεταξύ -360 και 360.

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```

Πολλαπλασιάζει το συστατικό απόχρωσης με την τιμή μιας παραμέτρου.

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```

Αλλάζει το συστατικό κορεσμού του χρώματος στην τιμή μιας παραμέτρου. Η παράμετρος κυμαίνεται μεταξύ 0 και 1.

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```

Προσθέτει την τιμή μιας παραμέτρου στο συστατικό κορεσμού του χρώματος. Η παράμετρος κυμαίνεται μεταξύ -1 και 1.

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```

Πολλαπλασιάζει το συστατικό κορεσμού με την τιμή μιας παραμέτρου.

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```

Αλλάζει το συστατικό φωτεινότητας του χρώματος στην τιμή μιας παραμέτρου. Η παράμετρος κυμαίνεται μεταξύ 0 και 1.

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```

Προσθέτει την τιμή μιας παραμέτρου στο συστατικό φωτεινότητας του χρώματος. Η παράμετρος κυμαίνεται μεταξύ -1 και 1.

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

Πολλαπλασιάζει το συστατικό φωτεινότητας με την τιμή μιας παραμέτρου.

### SetRed {#SetRed}
```
public static final int SetRed
```

Αλλάζει το κόκκινο συστατικό του χρώματος στην τιμή μιας παραμέτρου. Η παράμετρος κυμαίνεται μεταξύ 0 και 1.

### AddRed {#AddRed}
```
public static final int AddRed
```

Προσθέτει την τιμή μιας παραμέτρου στο κόκκινο συστατικό του χρώματος. Η παράμετρος κυμαίνεται μεταξύ -1 και 1.

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```

Πολλαπλασιάζει το κόκκινο συστατικό με μια παράμετρο.

### SetGreen {#SetGreen}
```
public static final int SetGreen
```

Αλλάζει το πράσινο συστατικό του χρώματος στην τιμή μιας παραμέτρου. Η παράμετρος κυμαίνεται μεταξύ 0 και 1.

### AddGreen {#AddGreen}
```
public static final int AddGreen
```

Προσθέτει μια παράμετρο στο πράσινο συστατικό του χρώματος. Η παράμετρος κυμαίνεται μεταξύ -1 και 1.

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```

Πολλαπλασιάζει το πράσινο συστατικό του χρώματος με την τιμή μιας παραμέτρου.

### SetBlue {#SetBlue}
```
public static final int SetBlue
```

Αλλάζει το μπλε συστατικό του χρώματος στην τιμή μιας παραμέτρου. Η παράμετρος κυμαίνεται μεταξύ 0 και 360.

### AddBlue {#AddBlue}
```
public static final int AddBlue
```

Προσθέτει την τιμή μιας παραμέτρου στο μπλε συστατικό του χρώματος. Η παράμετρος κυμαίνεται μεταξύ -1 και 1.

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```

Πολλαπλασιάζει το μπλε συστατικό του χρώματος με την τιμή μιας παραμέτρου.

### Gamma {#Gamma}
```
public static final int Gamma
```

Διόρθωση γάμμα. Η παράμετρος αγνοείται.

### InverseGamma {#InverseGamma}
```
public static final int InverseGamma
```

Αντίστροφη διόρθωση γάμμα. Η παράμετρος αγνοείται.