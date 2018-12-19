# Τελική αναφορά του μαθήματος Επικοινωνία Ανθρώπου-Υπολογιστή
### Ονοματεπώνυμο:ΦΟΥΡΝΑΡΗΣ ΓΕΩΡΓΙΟΣ
### Αριθμός Μητρώου:Π2017158

Η αναφορά αυτή αφορά την εργασία οπικοποίησης δεδομένων στο μάθημα "Επικοινωνία ανθρώπου υπολογιστή". Παρακάτω, ακολουθούν τα βήματα τα εργαλεία και οι τρόποι επίλυσης κάθε ερωτήματος της εργασίας με εικόνες και gifs που απεικονίζουν τα αποτελέσματα απο τις  προσθήκες τις αλλαγές όπως επίσης και τους κώδικες που χρησιμοποιήθηκαν. Επιπλέον, στην αναφορά περιλαμβάνονται τα συμπεράσματα στα οποία κατέληξα μέσω της ενασχόλησής μου με την συγκεκριμένη εργασία όπως επίσης και η βιβλιογραφία που χρησιμοποιήθηκε.

#### [Link αποθετηρίου](https://github.com/p17four/D3js-US-educational-attainment)
#### [Εκτελέσιμο link](https://p17four.github.io/D3js-US-educational-attainment/)

## Εισαγωγή
Στόχος της συγκεκριμένης εργασίας ηταν η επεξεργασία μίας web σελίδας με σκοπό την οπτικοποίηση των δεδομένων της.Με την χρήση των γλωσσών html,css και javascript έπρεπε να κάνουμε κάποιες μετατροπές στην ιστοσελίδα που αφορούσαν την μορφοποίηση του  περιεχομενό της και την λειτουργικοτητά της.Η εργασία χωρίστηκε σε 2 παραδοτέα. Το πρώτο είχε 5 ερωτήματα ενώ το δεύτερο 3.
Τα ζητούμενα του πρώτου παραδοτέου είχαν ως στόχο την αλλαγή των χρωμάτων και στα 3 γραφήματα, την αντικατάσταση στις διεπαφές (κουμπιά) του 2ου και 3ου γραφήματος με άλλες της επιλογής μας, όταν το ποντίκι διέρχεται επάνω από κάθε επιλογή του menu στην κορυφή της σελίδας, να ακούγεται κάποιος ήχος της επιλογής μας, κάθε φορά που το ποντίκι διέρχεται πάνω από κάποια πρόταση/κείμενο της σελίδας, να ακούγεται αυτόματα η αφήγηση του κειμένου (text-to-speech) και,επίσης, να εφαρμόσουμε responsive design στη σελίδα και κυρίως στο αρχικό menu έτσι ώστε να προσαρμόζεται σε οθόνες διαφορετικών διαστάσεων.
Τα ερωτήματα που περιείχε το δεύτερο παραδοτέο είχαν για τελικό σκοπό την τροποποίηση του κώδικα και του μενού έτσι ώστε κάθε στιγμή να είναι εμφανές μόνο ένα από τα 3 γραφήματα (δίχως να δημιουργούσαμε καινούργιο αρχείο), την αντικατάστηση καθενός από τα 3 αρχικά γραφήματα με κάποιο άλλο διαδραστικό γράφημα της D3js και σε μια καινούργια σελίδα, να τοποθετούσαμε αντίστοιχα 3 νέα διαδραστικά γραφήματα D3js της επιλογής μας, τα οποία θα οπτικοποιούσαν καινούργια στατιστικά δεδομένα που θα βρίσκαμε από κάποια επίσημη στατιστική αρχή.
Από τα παραπάνω δεν κατάφερα να υλοποιήσω το responsive design στα διαγράμματα , παρόλου πού τα κατάφερα στο menu και τα κείμενα.Ακόμα, δεν μπόρεσα να αλλάξω τα 3 αρχικά διαγράματα με 3 νέα όπως ζητούσε το 2ο ερώτημα του 2ου παραδοτέου.


## Σύντομη ανάλυση σχετικών έργων και εργαλείων

Για την ολοκλήρωση της εργασίας χρησιμοποιήθηκαν διάφορες μεθόδοι αλλά και εργαλεία.Αρχικά, μελέτησα προσεκτικά τις γλώσσες προγραμματισμού (html,css,javascript) για να καταφέρω να κατανοήσω καλύτερα τον υπάρχον κώδικα και τι μετατροπές που θα έπρεπε να κάνω. Για την μελέτη των γλωσσών πλοηγήθηκα σε site όπως το w3school, wlearn το Academy of Code και το javascript.com.Από άποψη λογισμικού, για την συγγραφή κώδικα χρησιμοποίησα το notepad++ καθώς διευκόλυνε την διαχείρηση πολλών ενεργειών με την άμεση προβολή των αλλαγών που πραγματοποιούσα.Το notepad++ παρέχει δυνατότητες για την διευκόλυνση συγγραφής κώδικα που δεν υπάρχουν στο github οι οποίες μου φάνηκαν αρκετά χρήσημες, έτσι αποφεύηκαν αρκετά συντακτικά λάθη και ήταν ένας καλός τρόπος εκμάθησης της γλώσσας.

##Μέθοδος και τεχνικές ανάπτυξης
Παρακάτω είναι οι μέθοδοι και οι τεχνικές που ακολούθησα στην εργασία:

Βήμα 1
Αρχικά, διάβασα απο διάφορα site την σύνταξη της κάθε γλώσσας καθώς ήταν απαραίτητο για την κατανόηση του κώδικα που έπρεπε να προσθέσω σε html, σε css και σε javascript. Τα site στα οποία απευθύνθηκα περισσότερο ειναι τα εξής :

w3school
academy of code
wlearn
javascript.com
codepen


Βήμα 2
Εφόσον κατανόησα πως λειτουργούν οι γλώσσες ξεκίνησα να επεμβαίνω στον κώδικα, να κάνω αλλαγές και να λύνω τα ζητήματα των παραδοτέων.

α)Βρήκα μέσα από το αρχείο javascript ότι γίνεται η αλλαγή των χρωμάτων στα απαιτούμενα σημεία.

β)Για την αλλαγή των διεπαφών άλλαξα τον υπάρχον κώδικα του style.css.

γ)Το συγκεκριμένο ερώτημα αποδείχθηκε πιο απαιτητικό καθώς έπρεπε να βρω μια συνάρτηση που θα καλούσε το αρχείου το ήχου, που είχα βρει νωρίτερα και είχα ανεβάσει στο branch, μέσα στην index.

δ)Βρήκα ακόμα μια νέα συνάρτηση πάλι για ήχο, responsiveVoice, αυτή τη φορά ήταν πιο εύκολο.Υπήρξε ακόμα η mouseover που βοήθησε στην επίλυση αυτού του ερωτήματος.

ε)Για το responsive design κατάφερα μόνο να το υλοποιήσω για ολόκληρη την σελίδα πλην των γραφημάτων.

ζ)Σε αυτό το ερώτημα έπρεπε να εμφανίζεται μόνο ένα γράφημα τη φορά. Με την βοήθεια της showhide(); επέλυσα το συγκεκριμένο ζητούμενο.

η)Το συγκεκριμένο ερώτημα δεν κατάφερα να το κάνω.

ι)Τέλος, δημιούργησα μια νέα σελίδα που περιείχε 3 νέα διαγράμματα, με τι λειτουργείες της προηγούμενης σελίδας, και με δεδομένα που βρήκα στην σελίδα EUROSTAT.


##Συμπεράσματα

Τα συμπεράσματα μετά την  ολοκλήρωση της εργασίας ήταν αρκετά.Καταρχάς, μελέτησα, κατανόησα και επεξεργάστηκα τις πιο διαδεδομένες γλώσσες προγραμματισμού για τις σελίδες στο web. Κατάλαβα πως λειτουργούν οι ιστοσελίδες και πόσο απαιτητικό είναι να φτιάξεις μια νέα σελίδα.Επιπλέον, αυτή η εργασία ήταν μια καλή εξάσκηση για τις δεξιότητές μου στο συγκεκριμένο τομέα και μου έδειξε μια πλευρά του προγραμματισμού που δεν είχα σκεφτεί πιο πριν.Επίσης, με εξοικίωσε με ιστοσελίδες όπως το github που πέρασα αρκετές ώρες προσπαθόντας να λύσω τη εργασία, το codepen που και εκεί χρειάστηκε να περάσω αρκετές ώρες και να κατανοήσω τις λειτουργείες του, έτσι τώρα έχω γνώσεις και εμπειρία σε αυτές.Τέλος, αυτή η εργασία μου έμαθε πως να ερευνώ σε βάθος και πως θα πρέπει να αναζητώ πληροφορίες σχετικές με το προγραμματισμό με ορθότερο τρόπο.


## Βιβλιογραφία και σύνδεσμοι σε σχετικές εργασίες
* [ΕΛΣΤΑΤ](http://www.statistics.gr/)
* [w3school](https://www.w3schools.com/default.asp)
* [javascript](https://www.javascript.com/)
* [wlearn](https://www.wlearn.gr/index.php/topmenu-118)
* [Academy of Code](https://www.academy-of-code.com/el/)
* [CodePen](https://codepen.io/)
* [responsive voice](https://responsivevoice.org/)
* [d3js](https://d3js.org/)
