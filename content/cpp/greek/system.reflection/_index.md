---
title: "System::Reflection"
second_title: Aspose.Slides για C++ API Αναφορά
description:
type: docs
weight: 755
url: /el/system.reflection/
---
## Κλάσεις

| Class | Description |
| --- | --- |
| [Assembly](./assembly/) | [Reflection](./) κλάση που περιγράφει τη συγκρότηση. Η υποστήριξη είναι περιορισμένη καθώς οι κανόνες διαφέρουν αρκετά μεταξύ C# και C++. Αντικείμενα αυτής της κλάσης πρέπει να καταλαμβάνονται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../system/makeobject/). Ποτέ μην δημιουργείτε αντίγραφο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς αυτό θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να την περάσετε σε συναρτήσεις ως όρισμα. |
| [AssemblyName](./assemblyname/) | Ορίζει το όνομα της συγκρότησης. Αντικείμενα αυτής της κλάσης πρέπει να καταλαμβάνονται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../system/makeobject/). Ποτέ μην δημιουργείτε αντίγραφο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς αυτό θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να την περάσετε σε συναρτήσεις ως όρισμα. |
| [AssemblyTypeRegistration](./assemblytyperegistration/) | Μοναδικό για την εγγραφή τύπου στην εκτελούμενη συγκρότηση. |
| [AssemblyTypeRegistrationBase](./assemblytyperegistrationbase/) | Βασικός τύπος για singletons για την εγγραφή τύπου στην εκτελούμενη συγκρότηση. |
| [ConstructorInfo](./constructorinfo/) | Παρέχει πρόσβαση στα μεταδεδομένα του κατασκευαστή. |
| [Details_ReflectionTypeLoadException](./details_reflectiontypeloadexception/) | ReflectionTypeLoadException εκτοξεύεται από τη μέθοδο Module.GetTypes εάν κάποια από τις κλάσεις σε ένα module αποτύχει να φορτωθεί. Ποτέ μην δημιουργείτε αντικείμενα αυτής της κλάσης χειροκίνητα. Χρησιμοποιήστε την κλάση ReflectionTypeLoadException αντί αυτού. Ποτέ μην τυλίγετε τα αντικείμενα της κλάσης ReflectionTypeLoadException σε [System::SmartPtr](../system/smartptr/). |
| [Details_TargetInvocationException](./details_targetinvocationexception/) | TargetInvocationException εκτοξεύεται από μεθόδους που κλήθηκαν μέσω reflection. Ποτέ μην δημιουργείτε αντικείμενα αυτής της κλάσης χειροκίνητα. Χρησιμοποιήστε την κλάση TargetInvocationException αντί αυτού. Ποτέ μην τυλίγετε τα αντικείμενα της κλάσης TargetInvocationException σε [System::SmartPtr](../system/smartptr/). |
| [FieldInfo](./fieldinfo/) | Ανακαλύπτει τα χαρακτηριστικά ενός πεδίου και παρέχει πρόσβαση στα μεταδεδομένα του πεδίου. |
| [MemberInfo](./memberinfo/) | Παρέχει πληροφορίες reflection για τα μέλη. Αντικείμενα αυτής της κλάσης πρέπει να καταλαμβάνονται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../system/makeobject/). Ποτέ μην δημιουργείτε αντίγραφο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς αυτό θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να την περάσετε σε συναρτήσεις ως όρισμα. |
| [MethodBase](./methodbase/) | Βασικές πληροφορίες για τη μέθοδο. Αντικείμενα αυτής της κλάσης πρέπει να καταλαμβάνονται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../system/makeobject/). Ποτέ μην δημιουργείτε αντίγραφο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς αυτό θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να την περάσετε σε συναρτήσεις ως όρισμα. |
| [MethodInfo](./methodinfo/) | Αναπαριστά πληροφορίες για τη μέθοδο κλάσης. |
| [PropertyInfo](./propertyinfo/) | Αναπαριστά πληροφορίες ιδιότητας. |
## Απαριθμήσεις

| Enum | Description |
| --- | --- |
| [BindingFlags](./bindingflags/) | Καθορίζει μέλη και τρόπους αναζήτησης τύπων και δεσμεύσεων. |
| [FieldAttributes](./fieldattributes/) | Αντικατοπτριζόμενα χαρακτηριστικά πεδίου. |
| [MemberTypes](./membertypes/) | Σημαδεύει κάθε τύπο μέλους. |
## Ορισμοί τύπων

| Typedef | Description |
| --- | --- |
| [ReflectionTypeLoadException](./reflectiontypeloadexception/) | ReflectionTypeLoadException εκτοξεύεται από τη μέθοδο Module.GetTypes εάν κάποια από τις κλάσεις σε ένα module αποτύχει να φορτωθεί. Ποτέ μην τυλίγετε τα αντικείμενα της κλάσης ReflectionTypeLoadException σε [System::SmartPtr](../system/smartptr/). |
| [TargetInvocationException](./targetinvocationexception/) | TargetInvocationException εκτοξεύεται από μεθόδους που κλήθηκαν μέσω reflection. Ποτέ μην τυλίγετε τα αντικείμενα της κλάσης TargetInvocationException σε [System::SmartPtr](../system/smartptr/). |