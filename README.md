# 📢 Concorsi inPA — Monitor Telegram

**Concorsi inPA** è un progetto indipendente che monitora il portale pubblico *InPA – Pubblica Amministrazione* e invia automaticamente su Telegram tutti i nuovi concorsi non appena vengono pubblicati.

L’obiettivo è offrire un canale unico, immediato e aggiornato in tempo reale per chi segue bandi e avvisi nella Pubblica Amministrazione.

---

## 🔗 Canale Telegram

➡️ **[t.me/Concorsi_inPA](https://t.me/Concorsi_inPA)**

Tutti i concorsi vengono inviati in un formato pulito con titolo, ente, sede, scadenza e link diretto al bando.

---

## 🧩 Come funziona

Il sistema effettua periodicamente una richiesta alle API pubbliche di InPA.  
Quando viene rilevato un concorso non ancora pubblicato nel canale:

1. ne estrae i dati principali  
2. li formatta in un messaggio leggibile  
3. invia il tutto direttamente su Telegram  

---

## 📬 Informazioni pubblicate

Per ogni concorso vengono estratti e inviati:

- 🏛 **Titolo del bando**  
- 🏢 **Ente di riferimento**  
- 📍 **Regione e città**  
- 👤 **Figura professionale**  
- 🗓 **Data di pubblicazione**  
- ⏳ **Data di scadenza**  
- 🔗 **Link al bando**  
- ✏️ **Breve descrizione (ripulita dall’HTML)**  

Le informazioni derivano *esclusivamente* dai dati pubblici resi disponibili dal portale.

---

## 📸 Screenshot
![Preview del bot](https://i.nuuls.com/rzEio.png)

