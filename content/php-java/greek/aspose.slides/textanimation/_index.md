---
title: TextAnimation
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs

url: /el/aspose.slides/textanimation/
---
## TextAnimation κλάση

Αναπαριστά την κίνηση κειμένου.

### TextAnimation {#TextAnimation}

| Όνομα | Περιγραφή |
| --- | --- |
| TextAnimation() |  |

**Επιστρέφει:**
TextAnimation

---

### addEffect {#addEffect}

| Όνομα | Περιγραφή |
| --- | --- |
| addEffect (int, int, int) | Προσθέτει νέο εφέ στο τέλος της τρέχουσας ακολουθίας ή στο τέλος των κινήσεων κειμένου ομάδας. Είναι έγκυρο μόνο αν ο αριθμός των παραγράφων κειμένου είναι ίσος ή μεγαλύτερος από τον αριθμό των εφέ αυτής της ομάδας! |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| effectType | int | Τύπος εφέ κίνησης EffectType |
| subtype | int | Υποτύποι εφέ κίνησης EffectSubtype |
| triggerType | int | Τύπος ενεργοποίησης εφέ EffectTriggerType |

**Επιστρέφει:**
[Effect](../effect)

---

### getBuildType {#getBuildType}

| Όνομα | Περιγραφή |
| --- | --- |
| getBuildType () | Λίστα τύπων κατασκευής (π.χ. Παράγραφος 1,2,3, Όλα Μαζί) της κίνησης κειμένου. Ανάγνωση/Εγγραφή BuildType. |

**Επιστρέφει:**
int

---

### getEffectAnimateBackgroundShape {#getEffectAnimateBackgroundShape}

| Όνομα | Περιγραφή |
| --- | --- |
| getEffectAnimateBackgroundShape () | Συνδεδεμένο σχήμα εφέ με την ομάδα ή όχι (null). Ανάγνωση/Εγγραφή IEffect. |

**Επιστρέφει:**
[Effect](../effect)

---

### setBuildType {#setBuildType}

| Όνομα | Περιγραφή |
| --- | --- |
| setBuildType (int) | Λίστα τύπων κατασκευής (π.χ. Παράγραφος 1,2,3, Όλα Μαζί) της κίνησης κειμένου. Ανάγνωση/Εγγραφή BuildType. |

**Επιστρέφει:**
void

---

### setEffectAnimateBackgroundShape {#setEffectAnimateBackgroundShape}

| Όνομα | Περιγραφή |
| --- | --- |
| setEffectAnimateBackgroundShape ([Effect](../effect)) | Συνδεδεμένο σχήμα εφέ με την ομάδα ή όχι (null). Ανάγνωση/Εγγραφή IEffect. |

**Επιστρέφει:**
void

---