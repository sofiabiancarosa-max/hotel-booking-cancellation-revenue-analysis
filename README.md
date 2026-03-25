# Hotel Booking Demand, Cancellation & Revenue Analysis

## Overview
Questo progetto analizza la domanda alberghiera, l’andamento dei prezzi, i ricavi e i fattori che influenzano le cancellazioni delle prenotazioni.  

L’obiettivo è trasformare un dataset grezzo di prenotazioni hotel in un flusso di lavoro completo di data analysis: pulizia dei dati in Python, creazione di feature derivate, costruzione di un dataset finale per Power BI e realizzazione di un report interattivo orientato al business.

Si tratta di un progetto di analisi dati end-to-end sulle prenotazioni alberghiere, che integra pulizia dati in Python, feature engineering, analisi esplorativa e dashboard Power BI focalizzate su domanda, ricavi e pattern di cancellazione.

---

## Business Goals
Le domande principali a cui il progetto cerca di rispondere sono:

- Quali hotel, segmenti e canali generano maggiore valore?
- Come variano prezzi e ricavi nel tempo?
- Quali fattori sono associati a un maggiore rischio di cancellazione?
- Quali pattern possono supportare decisioni commerciali e di revenue management?

---

## Tools Used
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Power BI**
- **GitHub**

---

## Project Workflow
Il progetto è stato sviluppato in più fasi:

1. **Data cleaning in Python**
   - rimozione di colonne sensibili/non utili
   - gestione dei missing values
   - rimozione dei duplicati
   - analisi e trattamento degli outlier
   - controllo della qualità del dataset

2. **Feature engineering**
   - creazione di nuove variabili utili all’analisi:
     - `total_nights`
     - `total_guests`
     - `season`
     - `revenue`
     - `lead_time_band`

3. **Exploratory Data Analysis**
   - confronto tra tipologie di hotel
   - analisi di ADR, revenue e booking patterns
   - analisi del cancellation rate per segmenti, canali e anticipo di prenotazione

4. **Power BI reporting**
   - costruzione di dashboard per:
     - overview generale
     - andamento prezzi e ricavi
     - cancellazioni per canale e segmento

---

## Files in This Repository
- `Hotel Booking Demand & Revenue Analysis.py`  
  Script Python con pulizia dati, feature engineering ed analisi esplorativa

- `Hotel Booking Demand & Analysis.html`  
  Notebook esportato in HTML con analisi e risultati

- `hotel_booking_final_for_powerbi.csv`  
  Dataset finale pronto per Power BI

- `hotel_preformance.pbix`  
  File Power BI del report finale

- `images/`  
  Screenshot delle pagine del report Power BI

---

## Dataset Preparation
Il dataset finale è stato costruito partendo da una base di prenotazioni alberghiere e preparato per l’analisi BI.

Tra gli interventi principali:
- sostituzione dei valori mancanti in variabili selezionate
- eliminazione dei record duplicati
- verifica della distribuzione delle variabili numeriche
- identificazione di valori anomali
- creazione di metriche più leggibili per analisi e reportistica

---

## Key Features Created
Per rendere il dataset più utile dal punto di vista analitico, sono state create alcune colonne derivate:

- **total_nights** → numero totale di notti prenotate
- **total_guests** → numero totale di ospiti
- **season** → stagione di riferimento della prenotazione
- **revenue** → ricavo stimato per prenotazione
- **lead_time_band** → fascia di anticipo della prenotazione

Queste variabili sono state utilizzate sia in Python sia nel report finale in Power BI.

---

## Main Insights
Dall’analisi emergono alcuni pattern principali:

- Le prenotazioni con **lead time più elevato** mostrano un **maggiore rischio di cancellazione**
- Il **Resort Hotel** presenta in media un **revenue per booking più alto** rispetto al City Hotel
- Alcuni **market segment** e **distribution channel** risultano più esposti alle cancellazioni
- Il **revenue** dipende soprattutto da **ADR** e **durata del soggiorno**
- Le cancellazioni non sono spiegate da una sola variabile numerica, ma da una combinazione di fattori commerciali e comportamentali

---

## Power BI Report Structure
Il report Power BI è organizzato in più sezioni:

### 1. Overview
Vista generale delle performance:
- prenotazioni
- ricavi
- ADR medio
- cancellation rate
- confronto tra tipologie di hotel

### 2. Prices & Revenue
Analisi dell’andamento di:
- ADR
- ricavi
- distribuzione delle prenotazioni
- segmenti e canali a maggiore valore

### 3. Cancellation Analysis
Focus su:
- cancellation rate per canale
- cancellation rate per segmento
- relazione tra lead time e cancellazioni
- individuazione di gruppi più a rischio

---

## Project Value
Questo progetto mostra un flusso completo di lavoro data-driven:

- preparazione e pulizia dati
- ragionamento analitico
- traduzione degli insight in dashboard
- collegamento tra analisi tecnica e interpretazione di business

È un esempio di progetto end-to-end utile per ruoli come:
- Data Analyst
- Business Analyst
- BI Analyst
- Commercial / Revenue Analyst

---

## How to Open the Report
Il report Power BI non è pubblicato online, ma il file `.pbix` è disponibile nel repository e può essere aperto con **Power BI Desktop**.

---

## Dashboard Preview

![Page 1](images/page1.png)
![Page 2](images/page2.png)
![Page 3](images/page3.png)
![Page 4](images/page4.png)
![Page 5](images/page5.png)
![Page 6](images/page6.png)
