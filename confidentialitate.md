---
title: Politica de confidențialitate
permalink: /confidentialitate
---

<!-- GENERAT de scripts/build-legal-site.mjs. Nu se editează aici:
     sursa este docs/confidentialitate.md, iar modificările de aici se pierd. -->
**Ultima actualizare: 3 septembrie 2026**

Adresa publică a acestui document:
<https://sebastian-personal-2026.github.io/whoup-legal/confidentialitate>

---

## Pe scurt

**WHOUP** îți arată cine e disponibil să iasă din casă în apropierea ta,
chiar acum. Ca să facă asta, are nevoie de poziția ta. Pentru că știm cât de
sensibil e lucrul ăsta, l-am construit cu trei reguli pe care le poți verifica
în felul în care se comportă aplicația:

1. **Poziția ta exactă nu ajunge niciodată la alți utilizatori.** Serverul o
   primește, dar celorlalți le dă doar celula de aproximativ 250 de metri în
   care te afli. Doi oameni din aceeași celulă primesc exact aceleași
   coordonate.
2. **Poziția se stochează doar cât timp ești disponibil.** Când oprești
   disponibilitatea, rândul cu poziția ta se șterge din baza de date. Nu e o
   setare pe care ai putea s-o uiți pornită.
3. **Data nașterii nu părăsește serverul.** Stă într-un tabel separat. Afară
   iese doar vârsta în ani.

Nu vindem date nimănui. Nu facem publicitate targetată. Nu folosim date de
localizare în alt scop decât cel pentru care e făcută aplicația.

---

## 1. Cine este operatorul

**EBEBE RETAIL CSA S.R.L.**, cu sediul în Str. Mărgeanului nr. 22, bl. M35,
sc. 2, et. 7, ap. 69, camera 1, Sector 5, București, România, CUI **42863783**,
înregistrată la Registrul Comerțului sub nr. **J40/9152/03.08.2020**, este
operatorul datelor tale cu caracter personal în sensul Regulamentului (UE)
2016/679 (GDPR).

Pentru orice întrebare sau cerere legată de datele tale, scrie la `whoup.contact@gmail.com`.

Nu am desemnat un responsabil cu protecția datelor (DPO): nu ne încadrăm în
niciunul dintre cazurile în care legea îl cere. Cererile le tratăm direct, la
adresa de mai sus.

---

## 2. Ce date colectăm, de ce, și în ce temei

### 2.1. Contul

| Dată | De ce |
|---|---|
| Adresa de email | Ca să te poți conecta și ca să-ți putem trimite resetarea parolei |
| Parola | Nu o vedem niciodată: se stochează sub formă de amprentă criptografică (hash) |

**Temei:** executarea contractului dintre tine și noi (art. 6 alin. 1 lit. b
GDPR) — fără cont, aplicația nu poate funcționa.

### 2.2. Profilul, vizibil celorlalți utilizatori

Numele afișat, descrierea, poza de profil (dacă alegi să pui una) sau avatarul
desenat, limbile vorbite, interesele, eticheta „nou în zonă", etichetele „la
întâlnire", genul (dacă alegi să-l completezi) și vârsta în ani.

Toate acestea sunt **publice pentru ceilalți utilizatori ai aplicației**. Le
completezi tu, iar aplicația funcționează și dacă lași aproape totul gol: poza
nu este obligatorie niciodată.

**Temei:** executarea contractului.

### 2.3. Data nașterii

Se stochează separat de restul profilului, într-un tabel din care **nu iese
niciodată în aplicație**. Din ea calculăm doar vârsta în ani, iar aceea se
vede pe profilul tău public.

O folosim în două scopuri: să afișăm vârsta și să verificăm pragul de 18 ani.

**Temei:** executarea contractului și obligația noastră de a nu permite accesul
minorilor (art. 6 alin. 1 lit. b și c).

### 2.4. Disponibilitatea

Intenția pentru care ești disponibil (o bere, o cafea, o masă, business, sport,
plimbat câinele, ieșit cu copiii, dating), pentru cât timp, nota liberă pe care
o scrii („la Ceaun, pe la 19:30") și dacă ai bifat „sunt deja acolo".

Cât timp disponibilitatea este activă, aceste date sunt **vizibile celorlalți
utilizatori din apropiere**. Ele expiră singure, la termenul ales de tine.

**Temei:** executarea contractului.

### 2.5. Locația — secțiunea care contează cel mai mult

Aplicația cere permisiunea de localizare doar cât timp o folosești în
prim-plan. **Nu urmărim poziția în fundal**, niciodată.

Ce se întâmplă exact cu ea:

- **Telefonul trimite poziția exactă** către serverul nostru, dar numai cât
  timp ai o disponibilitate activă **și** ai pornită setarea „Apari pe hartă".
- **Serverul o stochează**, ca să poată calcula ce e în jurul tău.
- **Ceilalți utilizatori primesc doar celula de ~250 m** în care te afli,
  rotunjită mereu la fel (nu cu zgomot aleatoriu, tocmai ca nimeni să nu poată
  deduce poziția exactă făcând media mai multor măsurători). Distanța afișată
  se calculează din poziția deja rotunjită.
- **Când oprești disponibilitatea, rândul cu poziția se șterge.** La fel dacă
  oprești „Apari pe hartă" sau dacă te deconectezi.

Poziția ta exactă nu este arătată niciunui alt utilizator, în nicio situație.

**Temei:** executarea contractului, pe baza permisiunii pe care o dai din
sistemul telefonului. Poți retrage permisiunea oricând din setările
telefonului; aplicația rămâne folosibilă, dar nu-ți mai poate arăta ce e lângă
tine.

### 2.6. Mesajele

Textul mesajelor (maximum 500 de caractere), momentul trimiterii și, dacă
trimiți un punct de întâlnire, coordonatele acelui punct și numele localului.

Punctul de întâlnire îl vede **doar persoana cu care vorbești**. Nu apare
nicăieri public.

Două lucruri pe care le spunem pe față:

- **Mesajele nu pot fi modificate sau șterse**, nici de tine, nici de
  destinatar. Este o măsură de siguranță: altfel, cine hărțuiește pe cineva
  și-ar putea șterge dovada exact înainte ca noi să ne uităm peste o raportare.
- **„Șterge conversația" o scoate din lista ta**, nu din a celuilalt și nu din
  baza de date. După ștergere nu mai vezi mesajele de dinainte; ele rămân
  stocate și pot fi citite de noi în cazul unei raportări.

**Temei:** executarea contractului, plus interesul nostru legitim de a menține
un mediu sigur (art. 6 alin. 1 lit. f).

### 2.7. Postările

Textul postării, locul de care o legi și termenul de expirare. Sunt publice
pentru utilizatorii din apropiere. Nu pot fi modificate — se șterg și se scriu
altele.

**Temei:** executarea contractului.

### 2.8. Siguranță: blocări și raportări

- **Blocările:** cine pe cine a blocat. Efectul este reciproc — dacă blochezi
  pe cineva, nu vă mai vedeți deloc, în niciun sens.
- **Raportările:** pe cine ai raportat, motivul ales, detaliile scrise de tine
  (opțional), și ce am hotărât noi în urma ei.

**Raportările nu se pot citi din aplicație**, nici măcar de cel care le-a
trimis. Un ecran care ar arăta „ai fost raportat de 3 ori" ar transforma
raportarea într-o armă.

O raportare **supraviețuiește ștergerii contului celui care a trimis-o**, dar
fără legătura cu el: informația despre persoana raportată nu dispare pentru că
a plecat cel care a semnalat-o.

**Temei:** interesul legitim de a proteja utilizatorii și obligațiile care ne
revin ca furnizor de serviciu (art. 6 alin. 1 lit. f și c).

### 2.9. Notificări

Dacă accepți notificările, stocăm un identificator al aparatului tău (token de
notificare) și platforma (iOS sau Android), ca să putem trimite notificarea
atunci când primești un mesaj. Dacă activezi digestul zilnic, stocăm ora la
care îl vrei și ziua în care ți l-am trimis ultima dată.

Tokenul aparține **aparatului**, nu contului: dacă altcineva se conectează pe
același telefon, tokenul trece la contul lui, ca notificările să nu ajungă la
fostul proprietar.

**Temei:** consimțământul tău, dat prin acceptarea notificărilor. Îl poți
retrage oricând din setările telefonului.

### 2.10. Erori tehnice

Când aplicația se defectează pe telefonul tău, ne trimite mesajul erorii, urma
tehnică a defectului, versiunea aplicației și platforma. Dacă ești conectat, se
trimite și identificatorul contului tău.

Nu citim aceste date din aplicație și nu le folosim în alt scop decât repararea
defectelor. Le păstrăm cel mult **90 de zile**, apoi se șterg automat.

**Temei:** interesul legitim de a menține aplicația în stare de funcționare.

### 2.11. Abonamentul

Stocăm doar dacă ai sau nu abonament activ.

**Plata trece integral prin App Store sau Google Play.** Nu vedem și nu
stocăm niciodată datele cardului tău. Pentru facturare și rambursări se aplică
politicile Apple, respectiv Google.

**Temei:** executarea contractului.

---

## 3. Cui transmitem datele

Nu vindem date. Nu le dăm brokerilor de date. Nu facem publicitate targetată.

Lucrăm cu următorii furnizori, strict pentru ca aplicația să funcționeze:

| Furnizor | Ce face | Ce vede |
|---|---|---|
| **Supabase** | Baza de date, autentificarea, stocarea pozelor | Toate datele descrise mai sus. Serverele sunt în Uniunea Europeană (Frankfurt, Germania) |
| **Expo** | Actualizările aplicației și livrarea notificărilor | Tokenul de notificare și conținutul notificării |
| **Apple (APNs)** și **Google (Firebase Cloud Messaging)** | Livrarea propriu-zisă a notificării pe telefon | Tokenul aparatului și conținutul notificării |
| **MapTiler** | Fundalul hărții (străzi, clădiri) | Adresa IP a telefonului și zona de hartă la care te uiți. **Nu primește poziția ta și nu știe cine ești** |
| **Apple App Store** / **Google Play** | Distribuția aplicației și plata abonamentului | Datele de plată, pe care noi nu le vedem |

Putem transmite date și autorităților, dacă ne obligă legea, sau dacă e necesar
pentru a preveni un pericol pentru viața ori integritatea cuiva.

Furnizorii de mai sus pot procesa date și în afara Uniunii Europene. Când se
întâmplă, transferul se face în temeiul clauzelor contractuale standard
aprobate de Comisia Europeană.

---

## 4. Cât timp păstrăm datele

| Ce | Cât |
|---|---|
| Contul și profilul | Cât timp ai cont |
| Poziția ta | Doar cât ai o disponibilitate activă. Se șterge automat când o oprești |
| Disponibilitățile | Expiră la termenul ales și nu mai apar nicăieri; rândul se șterge odată cu contul |
| Mesajele și conversațiile | Cât timp există contul |
| Postările | Expiră la termenul ales; se șterg odată cu contul |
| Blocările | Cât timp ai cont, sau până le anulezi tu |
| Raportările | Se păstrează și după ștergerea contului celui care a raportat, fără legătura cu el |
| Erorile tehnice | Cel mult 90 de zile |

---

## 5. Drepturile tale

Ai, în temeiul GDPR:

- **dreptul de acces** — să afli ce date avem despre tine;
- **dreptul la rectificare** — să corectezi ce e greșit; numele, descrierea,
  poza, limbile, interesele și data nașterii le poți schimba direct din
  aplicație;
- **dreptul la ștergere** — vezi secțiunea următoare;
- **dreptul la restricționarea prelucrării**;
- **dreptul la portabilitate** — să primești datele tale într-un format citibil
  de o mașină;
- **dreptul de opoziție** față de prelucrările întemeiate pe interesul nostru
  legitim;
- **dreptul de a-ți retrage consimțământul** pentru notificări și localizare,
  oricând, din setările telefonului.

Scrie la `whoup.contact@gmail.com` și îți răspundem în cel mult **30 de zile**.

Dacă nu ești mulțumit de răspuns, te poți adresa **Autorității Naționale de
Supraveghere a Prelucrării Datelor cu Caracter Personal** (ANSPDCP),
B-dul G-ral. Gheorghe Magheru 28-30, București, www.dataprotection.ro.

---

## 6. Cum îți ștergi contul

**Din aplicație:** `Profil → Cont → Șterge contul`. Este definitivă și nu poate
fi anulată.

Se șterg: contul, profilul, data nașterii, poza de profil, disponibilitățile,
postările, mesajele tale, blocările și tokenurile de notificare.

Rămân, fără legătura cu tine: raportările pe care le-ai trimis despre alți
utilizatori (ca informația despre cel raportat să nu dispară) și mesajele pe
care le-ai trimis, în conversațiile celorlalți — pentru același motiv pentru
care mesajele nu se pot șterge.

---

## 7. Vârsta minimă

Aplicația este **doar pentru persoane de 18 ani și peste**. Pragul este impus
la înscriere și la orice modificare ulterioară a datei nașterii.

Dacă afli că un minor și-a făcut cont, scrie-ne la `whoup.contact@gmail.com` și îl ștergem.

---

## 8. Securitate

Datele stau pe servere în Uniunea Europeană, iar accesul la ele este
restricționat la nivel de bază de date: fiecare utilizator poate citi doar ce
are dreptul să citească, iar regula se aplică pe server, nu în aplicație — o
aplicație modificată nu poate ocoli nimic.

Niciun sistem nu e perfect sigur. Dacă se produce o breșă care îți pune în
pericol drepturile, te anunțăm și anunțăm ANSPDCP în cel mult 72 de ore, cum
cere legea.

---

## 9. Modificări ale acestei politici

Când o modificăm, actualizăm data de la început. Dacă schimbarea e importantă
— de exemplu dacă am începe să colectăm date noi — te anunțăm în aplicație
înainte să intre în vigoare.

---

## 10. Contact

**EBEBE RETAIL CSA S.R.L.** · CUI 42863783 · J40/9152/03.08.2020
Str. Mărgeanului nr. 22, bl. M35, sc. 2, et. 7, ap. 69, camera 1, Sector 5,
București, România · `whoup.contact@gmail.com`
