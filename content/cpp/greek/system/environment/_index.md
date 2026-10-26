---
title: Environment
second_title: Aspose.Slides για C++ - Αναφορά API
description: Υπηρεσίες περιβάλλοντος. Αυτός είναι ένας static τύπος χωρίς υπηρεσίες instance. Δεν πρέπει ποτέ να δημιουργείτε instances του με κανέναν τρόπο.
type: docs
weight: 1600
url: /el/system/environment/
---
## Environment δομή

[Environment](./) υπηρεσίες. Αυτό είναι ένας static τύπος χωρίς instance υπηρεσίες. Δεν πρέπει ποτέ να δημιουργείτε instances του με κανέναν τρόπο.

```cpp
class Environment
```

## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| static void [Exit](./exit/)(int) | Τερματίζει τη τρέχουσα διαδικασία και επιστρέφει τον καθορισμένο κωδικό εξόδου στο λειτουργικό σύστημα. |
| static [String](../string/) [ExpandEnvironmentVariables](./expandenvironmentvariables/)(const [String](../string/)\&) | Αντικαθιστά τα ονόματα των μεταβλητών περιβάλλοντος που βρέθηκαν στη δεδομένη συμβολοσειρά με τις τιμές των μεταβλητών αυτών και επιστρέφει τη δημιουργημένη συμβολοσειρά. |
| static void [FailFast](./failfast/)(const [String](../string/)\&) | Τερματίζει βίαια τη τρέχουσα διαδικασία. |
| static [String](../string/) [get_CommandLine](./get_commandline/)() | Επιστρέφει τη γραμμή εντολών που χρησιμοποιήθηκε για την εκκίνηση της τρέχουσας διαδικασίας. |
| static [String](../string/) [get_CurrentDirectory](./get_currentdirectory/)() | Επιστρέφει τη διαδρομή προς τον τρέχοντα ενεργό φάκελο. |
| static int [get_ExitCode](./get_exitcode/)() | Επιστρέφει τον κωδικό εξόδου της τρέχουσας διαδικασίας. |
| static **bool** [get_HasShutdownStarted](./get_hasshutdownstarted/)() | Ελέγχει εάν η τερματισμός βρίσκεται σε εξέλιξη. Not implemented. |
| static **bool** [get_Is64BitProcess](./get_is64bitprocess/)() | Επιστρέφει true για εκτελέσιμα/βιβλιοθήκες πλατφόρμας 64-bit. |
| static [String](../string/) [get_MachineName](./get_machinename/)() | Επιστρέφει το όνομα NetBIOS αυτού του υπολογιστή. |
| static [String](../string/) [get_NewLine](./get_newline/)() | Επιστρέφει τη συμβολοσειρά νέας γραμμής που ορίζεται για το τρέχον περιβάλλον. |
| static const [OperatingSystem](../operatingsystem/)\& [get_OSVersion](./get_osversion/)() | Επιστρέφει το αντικείμενο [OperatingSystem](../operatingsystem/) που περιέχει πληροφορίες για το τρέχον λειτουργικό σύστημα. |
| static int [get_ProcessorCount](./get_processorcount/)() | Επιστρέφει τον αριθμό των επεξεργαστών ή του τρέχοντος μηχανήματος. |
| static [String](../string/) [get_StackTrace](./get_stacktrace/)() | Επιστρέφει τη συμβολοσειρά που περιέχει τις πληροφορίες του τρέχοντος stack trace. |
| static [String](../string/) [get_SystemDirectory](./get_systemdirectory/)() | Επιστρέφει τη διαδρομή προς τον φάκελο του συστήματος. |
| static int [get_TickCount](./get_tickcount/)() | Επιστρέφει τον αριθμό των χιλιοστών του δευτερολέπτου που πέρασαν από την εκκίνηση του συστήματος. |
| static [String](../string/) [get_UserDomainName](./get_userdomainname/)() | Επιστρέφει το όνομα του δικτυακού domain του τρέχοντος χρήστη. |
| static **bool** [get_UserInteractive](./get_userinteractive/)() | Καθορίζει εάν η τρέχουσα διαδικασία εκτελείται σε λειτουργία αλληλεπίδρασης χρήστη. |
| static [String](../string/) [get_UserName](./get_username/)() | Επιστρέφει το όνομα του χρήστη που είναι αυτή τη στιγμή συνδεδεμένος στο λειτουργικό σύστημα [Windows](../../system.windows/). |
| static [Version](../version/) [get_Version](./get_version/)() | Επιστρέφει το αντικείμενο [Version](../version/) που αντιπροσωπεύει τις πληροφορίες σχετικά με την έκδοση του κοινόχρηστου runtime γλώσσας. Ο αριθμός έκδοσης που επιστρέφεται από αυτή τη μέθοδο είναι μάλλον ψευδής και δεν σημαίνει ότι όλες οι κλάσεις βιβλιοθήκης συμπεριφέρονται σύμφωνα με την επιστρεφόμενη έκδοση. |
| static **int64_t** [get_WorkingSet](./get_workingset/)() | Επιστρέφει την ποσότητα φυσικής μνήμης που έχει αντιστοιχιστεί στο πλαίσιο της διαδικασίας. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetCommandLineArgs](./getcommandlineargs/)() | Επιστρέφει έναν πίνακα που περιέχει τα επιχειρήματα της γραμμής εντολών που χρησιμοποιήθηκαν για την εκκίνηση της τρέχουσας διαδικασίας. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&) | Επιστρέφει την τιμή της καθορισμένης μεταβλητής περιβάλλοντος που σχετίζεται με την τρέχουσα διαδικασία. |
| static [String](../string/) [GetEnvironmentVariable](./getenvironmentvariable/)(const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | Επιστρέφει την τιμή της καθορισμένης μεταβλητής περιβάλλοντος από τη συγκεκριμένη τοποθεσία. |
| static [String](../string/) [GetEnvironmentVariableA](./getenvironmentvariablea/)(const [String](../string/)\&) | Επιστρέφει την τιμή της καθορισμένης μεταβλητής περιβάλλοντος που σχετίζεται με την τρέχουσα διαδικασία. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)() | Επιστρέφει ένα λεξικό που περιέχει όλα τα ονόματα των μεταβλητών περιβάλλοντος και τις τιμές τους που σχετίζονται με την τρέχουσα διαδικασία. |
| static [Collections::Generic::DictionaryPtr](../../system.collections.generic/dictionaryptr/)\<[String](../string/), [String](../string/)\> [GetEnvironmentVariables](./getenvironmentvariables/)([EnvironmentVariableTarget](../environmentvariabletarget/)) | Επιστρέφει ένα λεξικό που περιέχει όλα τα ονόματα των μεταβλητών περιβάλλοντος και τις τιμές τους από την καθορισμένη τοποθεσία. |
| static [String](../string/) [GetEnvironmentVariableW](./getenvironmentvariablew/)(const [String](../string/)\&) | Επιστρέφει την τιμή της καθορισμένης μεταβλητής περιβάλλοντος που σχετίζεται με την τρέχουσα διαδικασία. |
| static [String](../string/) [GetFolderPath](./getfolderpath/)([SpecialFolder](./specialfolder/)) | Επιστρέφει πλήρως καθορισμένη διαδρομή προς τον καθορισμένο φάκελο του συστήματος. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetLogicalDrives](./getlogicaldrives/)() | Επιστρέφει έναν πίνακα που περιέχει τα ονόματα όλων των λογικών δίσκων στον τρέχοντα υπολογιστή. |
| static **bool** [IsWindowsSubsystemForLinux](./iswindowssubsystemforlinux/)() | Επιστρέφει true μόνο για WSL. |
| static void [set_CurrentDirectory](./set_currentdirectory/)(const [String](../string/)\&) | Ορίζει τον καθορισμένο φάκελο ως τρέχον ενεργό φάκελο. |
| static void [set_ExitCode](./set_exitcode/)(int) | Ορίζει την καθορισμένη τιμή ως κωδικό εξόδου για την τρέχουσα διαδικασία. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&) | ΔΕΝ ΕΥΚΟΝΟΠΟΙΗΘΗΚΕ. |
| static void [SetEnvironmentVariable](./setenvironmentvariable/)(const [String](../string/)\&, const [String](../string/)\&, [EnvironmentVariableTarget](../environmentvariabletarget/)) | ΔΕΝ ΕΥΚΟΝΟΠΟΙΗΘΗΚΕ. |

## Καταχωρίσεις

| Καταχώριση | Περιγραφή |
| --- | --- |
| [SpecialFolder](./specialfolder/) | Αντιπροσωπεύει τους ειδικούς φακέλους του συστήματος. |

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)