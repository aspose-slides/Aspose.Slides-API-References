---
title: ColorTransformOperation
second_title: Αναφορά API Aspose.Slides για Java
description: Ορίζει την λειτουργία μετασχηματισμού χρώματος.
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
| [Tint](#Tint) | Τονίζει το χρώμα. |
| [Shade](#Shade) | Σκιαρίζει το χρώμα. |
| [Complement](#Complement) | Αλλάζει το χρώμα σε συμπληρωματικό RGB. |
| [Inverse](#Inverse) | Αλλάζει το χρώμα σε αντιστροφή. |
| [Grayscale](#Grayscale) | Αλλάζει το χρώμα σε γκρι με την ίδια φωτεινότητα. |
| [SetAlpha](#SetAlpha) | Ορίζει τη συστατική άλφα του χρώματος. |
| [AddAlpha](#AddAlpha) | Προσθέτει την τιμή της παραμέτρου σε μια συστατική άλφα του χρώματος. |
| [MultiplyAlpha](#MultiplyAlpha) | Πολλαπλασιάζει μια συστατική άλφα με την τιμή της παραμέτρου. |
| [SetHue](#SetHue) | Αλλάζει τη συστατική απόχρωση του χρώματος στην τιμή της παραμέτρου. |
| [AddHue](#AddHue) | Προσθέτει την τιμή της παραμέτρου στη συστατική απόχρωση του χρώματος. |
| [MultiplyHue](#MultiplyHue) | Πολλαπλασιάζει τη συστατική απόχρωση με την τιμή της παραμέτρου. |
| [SetSaturation](#SetSaturation) | Αλλάζει τη συστατική κορεσμού του χρώματος στην τιμή της παραμέτρου. |
| [AddSaturation](#AddSaturation) | Προσθέτει την τιμή της παραμέτρου στη συστατική κορεσμού του χρώματος. |
| [MultiplySaturation](#MultiplySaturation) | Πολλαπλασιάζει τη συστατική κορεσμού με την τιμή της παραμέτρου. |
| [SetLuminance](#SetLuminance) | Αλλάζει τη συστατική φωτεινότητας του χρώματος στην τιμή της παραμέτρου. |
| [AddLuminance](#AddLuminance) | Προσθέτει την τιμή της παραμέτρου στη συστατική φωτεινότητα του χρώματος. |
| [MultiplyLuminance](#MultiplyLuminance) | Πολλαπλασιάζει τη συστατική φωτεινότητα με την τιμή της παραμέτρου. |
| [SetRed](#SetRed) | Αλλάζει το κόκκινο συστατικό του χρώματος στην τιμή της παραμέτρου. |
| [AddRed](#AddRed) | Προσθέτει την τιμή της παραμέτρου στο κόκκινο συστατικό του χρώματος. |
| [MultiplyRed](#MultiplyRed) | Πολλαπλασιάζει το κόκκινο συστατικό με την παράμετρο. |
| [SetGreen](#SetGreen) | Αλλάζει το πράσινο συστατικό του χρώματος στην τιμή της παραμέτρου. |
| [AddGreen](#AddGreen) | Προσθέτει την παράμετρο στο πράσινο συστατικό του χρώματος. |
| [MultiplyGreen](#MultiplyGreen) | Πολλαπλασιάζει το πράσινο συστατικό του χρώματος με την τιμή της παραμέτρου. |
| [SetBlue](#SetBlue) | Αλλάζει το μπλε συστατικό του χρώματος στην τιμή της παραμέτρου. |
| [AddBlue](#AddBlue) | Προσθέτει την τιμή της παραμέτρου στο μπλε συστατικό του χρώματος. |
| [MultiplyBlue](#MultiplyBlue) | Πολλαπλασιάζει το μπλε συστατικό του χρώματος με την τιμή της παραμέτρου. |
| [Gamma](#Gamma) | Διόρθωση γάμμα. |
| [InverseGamma](#InverseGamma) | Αντίστροφη διόρθωση γάμμα. |
### Tint {#Tint}
```
public static final int Tint
```

Τονίζει το χρώμα. Η παράμετρος είναι στο εύρος μεταξύ 0 (αρχικό χρώμα) και 1 (λευκό).

### Shade {#Shade}
```
public static final int Shade
```

Σκιαρίζει το χρώμα. Η παράμετρος είναι στο εύρος μεταξύ 0 (αρχικό χρώμα) και 1 (μαύρο).

### Complement {#Complement}
```
public static final int Complement
```

Αλλάζει το χρώμα σε συμπληρωματικό RGB. m = Max(r, g, b); r = m - r; g = m - g; b = m - b;

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

Ορίζει τη συστατική άλφα του χρώματος. Η παράμετρος είναι στο εύρος μεταξύ 0 (διαυγές) και 1 (αδιαφανές).

### AddAlpha {#AddAlpha}
```
public static final int AddAlpha
```

Προσθέτει την τιμή της παραμέτρου σε μια συστατική άλφα του χρώματος. Η παράμετρος είναι στο εύρος μεταξύ -1 και 1.

### MultiplyAlpha {#MultiplyAlpha}
```
public static final int MultiplyAlpha
```

Πολλαπλασιάζει μια συστατική άλφα με την τιμή της παραμέτρου.

### SetHue {#SetHue}
```
public static final int SetHue
```

Αλλάζει τη συστατική απόχρωση του χρώματος στην τιμή της παραμέτρου. Η παράμετρος είναι στο εύρος μεταξύ 0 και 360.

### AddHue {#AddHue}
```
public static final int AddHue
```

Προσθέτει την τιμή της παραμέτρου στη συστατική απόχρωση του χρώματος. Η παράμετρος είναι στο εύρος μεταξύ -360 και 360.

### MultiplyHue {#MultiplyHue}
```
public static final int MultiplyHue
```

Πολλαπλασιάζει τη συστατική απόχρωση με την τιμή της παραμέτρου.

### SetSaturation {#SetSaturation}
```
public static final int SetSaturation
```

Αλλάζει τη συστατική κορεσμού του χρώματος στην τιμή της παραμέτρου. Η παράμετρος είναι στο εύρος μεταξύ 0 και 1.

### AddSaturation {#AddSaturation}
```
public static final int AddSaturation
```

Προσθέτει την τιμή της παραμέτρου στη συστατική κορεσμού του χρώματος. Η παράμετρος είναι στο εύρος μεταξύ -1 και 1.

### MultiplySaturation {#MultiplySaturation}
```
public static final int MultiplySaturation
```

Πολλαπλασιάζει τη συστατική κορεσμού με την τιμή της παραμέτρου.

### SetLuminance {#SetLuminance}
```
public static final int SetLuminance
```

Αλλάζει τη συστατική φωτεινότητας του χρώματος στην τιμή της παραμέτρου. Η παράμετρος είναι στο εύρος μεταξύ 0 και 1.

### AddLuminance {#AddLuminance}
```
public static final int AddLuminance
```

Προσθέτει την τιμή της παραμέτρου στη συστατική φωτεινότητα του χρώματος. Η παράμετρος είναι στο εύρος μεταξύ -1 και 1.

### MultiplyLuminance {#MultiplyLuminance}
```
public static final int MultiplyLuminance
```

Πολλαπλασιάζει τη συστατική φωτεινότητα με την τιμή της παραμέτρου.

### SetRed {#SetRed}
```
public static final int SetRed
```

Αλλάζει το κόκκινο συστατικό του χρώματος στην τιμή της παραμέτρου. Η παράμετρος είναι στο εύρος μεταξύ 0 και 1.

### AddRed {#AddRed}
```
public static final int AddRed
```

Προσθέτει την τιμή της παραμέτρου στο κόκκινο συστατικό του χρώματος. Η παράμετρος είναι στο εύρος μεταξύ -1 και 1.

### MultiplyRed {#MultiplyRed}
```
public static final int MultiplyRed
```

Πολλαπλασιάζει το κόκκινο συστατικό με την παράμετρο.

### SetGreen {#SetGreen}
```
public static final int SetGreen
```

Αλλάζει το πράσινο συστατικό του χρώματος στην τιμή της παραμέτρου. Η παράμετρος είναι στο εύρος μεταξύ 0 και 1.

### AddGreen {#AddGreen}
```
public static final int AddGreen
```

Προσθέτει την παράμετρο στο πράσινο συστατικό του χρώματος. Η παράμετρος είναι στο εύρος μεταξύ -1 και 1.

### MultiplyGreen {#MultiplyGreen}
```
public static final int MultiplyGreen
```

Πολλαπλασιάζει το πράσινο συστατικό του χρώματος με την τιμή της παραμέτρου.

### SetBlue {#SetBlue}
```
public static final int SetBlue
```

Αλλάζει το μπλε συστατικό του χρώματος στην τιμή της παραμέτρου. Η παράμετρος είναι στο εύρος μεταξύ 0 και 360.

### AddBlue {#AddBlue}
```
public static final int AddBlue
```

Προσθέτει την τιμή της παραμέτρου στο μπλε συστατικό του χρώματος. Η παράμετρος είναι στο εύρος μεταξύ -1 και 1.

### MultiplyBlue {#MultiplyBlue}
```
public static final int MultiplyBlue
```

Πολλαπλασιάζει το μπλε συστατικό με την τιμή της παραμέτρου.

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