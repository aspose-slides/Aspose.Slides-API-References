---
title: MathPhantom
second_title: Aspose.Slides για C++ API Αναφορά
description: "Αντιπροσωπεύει ένα φανταστικό μαθηματικό αντικείμενο (<m:phant>) που επηρεάζει τη διάταξη του θυγατρικού στοιχείου του χωρίς απαραίτητα να το εμφανίζει. Ένα φανταστικό μπορεί να κρύβει τη βασική του έκφραση ενώ διατηρεί το πλάτος, το ύψος ή το βάθος του ώστε να ευθυγραμμίζει τύπους ή να διατηρεί χώρο. Η ορατότητα και η συμπεριφορά γεωμετρίας ελέγχονται από ιδιότητες όπως Show, ZeroWid, ZeroAsc, ZeroDesc και Transp."
type: docs
weight: 1028
url: /el/aspose.slides.mathtext/mathphantom/
---
## MathPhantom κλάση

Αντιπροσωπεύει ένα φανταστικό μαθηματικό αντικείμενο (<m:phant>) που επηρεάζει τη διάταξη του θυγατρικού στοιχείου της χωρίς απαραίτητα να το εμφανίζει. Ένα φανταστικό μπορεί να κρύβει την βασική έκφραση του ενώ διατηρεί το πλάτος, το ύψος ή το βάθος του για να ευθυγραμμίζει τύπους ή να διατηρεί χώρο. Η ορατότητα και η συμπεριφορά γεωμετρίας ελέγχονται από ιδιότητες όπως Show, ZeroWid, ZeroAsc, ZeroDesc, και Transp.

```cpp
class MathPhantom : public Aspose::Slides::MathText::MathElementBase,
                    public Aspose::Slides::MathText::IMathPhantom,
                    public Aspose::Slides::MathText::IHasControlCharacterProperties
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../mathelementbase/accent/)(char16_t) override | Ορίζει ένα σημάδι τόνου (έναν χαρακτήρα στην κορυφή αυτού του στοιχείου) |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Δέχεται τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτό το στιγμιότυπο ως όρισμα |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::String](../../system/string/)) override | Δέχεται τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτό το στιγμιότυπο ως όρισμα |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) override | Δέχεται τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτό το στιγμιότυπο ως όρισμα |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Δέχεται τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτό το στιγμιότυπο ως όρισμα και το καθορισμένο πρόσθετο όρισμα |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) override | Δέχεται τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτό το στιγμιότυπο ως όρισμα και το καθορισμένο πρόσθετο όρισμα |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Δημιουργεί κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/)) override | Δημιουργεί κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) override | Δημιουργεί κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) override | Δημιουργεί κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)() override | Τυλίγει ένα μαθηματικό στοιχείο σε παρενθέσεις |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)(char16_t, char16_t) override | Τυλίγει ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες, όπως παρενθέσεις ή άλλους χαρακτήρες, ως πλαίσιο |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με στυλ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής με στυλ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση σημειακών αριθμών σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, ούτε και με NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση σημειακών αριθμών σε στυλ C#, όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, ούτε και με NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Δέχεται μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτό το στιγμιότυπο ως όνομα συνάρτησης |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::String](../../system/string/)) override | Δέχεται μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτό το στιγμιότυπο ως όνομα συνάρτησης |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [get_Base](./get_base/)() override | Βασικό όρισμα |
| **bool** [get_Show](./get_show/)() override | Λαμβάνει μια τιμή που υποδεικνύει εάν το βασικό στοιχείο εμφανίζεται |
| **bool** [get_Transp](./get_transp/)() override | Λαμβάνει μια τιμή που υποδεικνύει εάν το φανταστικό είναι διαφανές για κανόνες διάστιξης βάσει κλάσεων |
| **bool** [get_ZeroAsc](./get_zeroasc/)() override | Λαμβάνει μια τιμή που υποδεικνύει εάν η άνοδος (ύψος πάνω από τη γραμμή βάσης) του βασικού στοιχείου πρέπει να θεωρείται μηδέν |
| **bool** [get_ZeroDesc](./get_zerodesc/)() override | Λαμβάνει μια τιμή που υποδεικνύει εάν η καθοδική (βάθος κάτω από τη γραμμή βάσης) του βασικού στοιχείου πρέπει να θεωρείται μηδέν |
| **bool** [get_ZeroWidth](./get_zerowidth/)() override | Λαμβάνει μια τιμή που υποδεικνύει εάν το πλάτος του βασικού στοιχείου πρέπει να θεωρείται μηδέν |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](./getchildren/)() override | Λαμβάνει τα στοιχεία των παιδιών |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφορών που σχετίζεται με το αντικείμενο |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία κατακερματισμού προσαρμοσμένων αντικειμένων |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)() override | Τοποθετεί αυτό το στοιχείο σε μια ομάδα χρησιμοποιώντας μια κάτω αγκύλη |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) override | Τοποθετεί αυτό το στοιχείο σε μια ομάδα χρησιμοποιώντας έναν χαρακτήρα ομαδοποίησης, όπως η κάτω αγκύλη ή άλλον |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) override | Λαμβάνει το ολοκλήρωμα |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Λαμβάνει το ολοκλήρωμα |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/)) override | Λαμβάνει το ολοκλήρωμα χωρίς όρια |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) override | Λαμβάνει το ολοκλήρωμα |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | Λαμβάνει το ολοκλήρωμα |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αποτελεί παράδειγμα τύπου που περιγράφεται από το targetType. Αναλογία του τελεστή C# 'is' |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Συνδέει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::String](../../system/string/)) override | Συνδέει ένα μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ |
| void [Lock](../../system/object/lock/)() | Υλοποιεί την εντολή κλειδώματος C# lock(). Κληθεί απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/) |
|  [MathPhantom](./mathphantom/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [MathPhantom](./) χρησιμοποιώντας το καθορισμένο βασικό μαθηματικό στοιχείο |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Δημιουργεί έναν N-δίου τελεστή |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | Δημιουργεί έναν N-δίου τελεστή |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την κατασκευή αντιγράφων υποκλάσεων |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την κατασκευή αντιγράφων υποκλάσεων |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../mathelementbase/overbar/)() override | Τοποθετεί μια μπάρα στην κορυφή αυτού του στοιχείου |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Καθορίζει τη μαθηματική ρίζα του δοσμένου βαθμού από το καθορισμένο όρισμα |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::String](../../system/string/)) override | Καθορίζει τη μαθηματική ρίζα του δοσμένου βαθμού από το καθορισμένο όρισμα |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει κατά αναφορά αντικείμενο τύπου τιμής με nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφορών κατά την καθορισμένη τιμή |
| void [set_Show](./set_show/)(**bool**) override | Ορίζει μια τιμή που υποδεικνύει εάν το βασικό στοιχείο εμφανίζεται |
| void [set_Transp](./set_transp/)(**bool**) override | Ορίζει μια τιμή που υποδεικνύει εάν το φανταστικό είναι διαφανές για κανόνες διάστιξης βάσει κλάσεων |
| void [set_ZeroAsc](./set_zeroasc/)(**bool**) override | Ορίζει μια τιμή που υποδεικνύει εάν η άνοδος (ύψος πάνω από τη γραμμή βάσης) του βασικού στοιχείου πρέπει να θεωρείται μηδέν |
| void [set_ZeroDesc](./set_zerodesc/)(**bool**) override | Ορίζει μια τιμή που υποδεικνύει εάν η καθοδική (βάθος κάτω από τη γραμμή βάσης) του βασικού στοιχείου πρέπει να θεωρείται μηδέν |
| void [set_ZeroWidth](./set_zerowidth/)(**bool**) override | Ορίζει μια τιμή που υποδεικνύει εάν το πλάτος του βασικού στοιχείου πρέπει να θεωρείται μηδέν |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Λαμβάνει το κάτω όριο |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::String](../../system/string/)) override | Λαμβάνει το κάτω όριο |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Δημιουργεί δείκτη |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::String](../../system/string/)) override | Δημιουργεί δείκτη |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) override | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) override | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Δημιουργεί εκθέτη |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::String](../../system/string/)) override | Δημιουργεί εκθέτη |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το ν-οστό όρισμα προτύπου ως αδύναμη αναφορά (αντί για κοινόχρηστη). Επιτρέπει την αλλαγή δεικτών σε containers σε αδύναμη λειτουργία |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Λαμβάνει το άνω όριο |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::String](../../system/string/)) override | Λαμβάνει το άνω όριο |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφορών |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)() override | Τοποθετεί αυτό το στοιχείο σε ένα πλαίσιο-κουτί |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) override | Τοποθετεί αυτό το στοιχείο σε ένα πλαίσιο-κουτί |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../mathelementbase/tobox/)() override | Τοποθετεί αυτό το στοιχείο σε ένα μη-οπτικό κουτί (λογική ομαδοποίηση) που χρησιμοποιείται για την ομαδοποίηση των στοιχείων μιας εξίσωσης ή άλλου μαθηματικού κειμένου. Ένα κουτιοποιημένο αντικείμενο μπορεί (για παράδειγμα) να λειτουργεί ως προσομοιωτής τελεστή με ή χωρίς σημείο στοίχισης, να λειτουργεί ως σημείο αλλαγής γραμμής, ή να ομαδοποιείται ώστε να μην επιτρέπεται αλλαγή γραμμής εντός |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../mathelementbase/tomatharray/)() override | Τοποθετεί σε κατακόρυφη διάταξη |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)) |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../mathelementbase/underbar/)() override | Τοποθετεί μια μπάρα στον πάτο αυτού του στοιχείου |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την εντολή κλειδώματος C# lock() για ξεκλείδωμα. Κληθεί απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων |

## Παρατηρήσεις

Παράδειγμα:
```cpp
System::SharedPtr<IMathPhantom> phantom = System::MakeObject<MathPhantom>(System::MakeObject<MathematicalText>(u"1/2"));
phantom->set_Show(false); // Απόκρυψη του περιεχομένου
phantom->set_ZeroWidth(false); // Διατήρηση του πλάτους
```

## Δείτε επίσης

* Κλάση [MathElementBase](../mathelementbase/)
* Κλάση [IMathPhantom](../imathphantom/)
* Κλάση [IHasControlCharacterProperties](../ihascontrolcharacterproperties/)
* Ονομαχώρος [Aspose::Slides::MathText](../)
* Βιβλιοθήκη [Aspose.Slides](../../)