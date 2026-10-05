# Akbar & Riswana — Nikkah Invitation Website

A luxury, interactive Islamic Nikkah invitation website styled in **Pista Green and Off-White**.

---

## ✨ Details Configured

- **Couple**: Akbar & Riswana
- **Monogram**: A & R (English) · ا & ر (Arabic Alif & Ra)
- **Ceremony**: The Nikah Ceremony (Single Event)
- **Date**: Saturday, 17 October 2026 (`17.10.2026`)
- **Hijri Date**: 6 Jumada Al-Awwal 1448 · ٦ جمادى الأولى ١٤٤٨
- **Venue**: V. P. MAMU COMMUNITY HALL, ANDATHODE — THRISSUR, KERALA
- **Location Link**: [Google Maps](https://maps.app.goo.gl/wbC4Cchs4wCedarr9?g_st=iw)
- **Color Theme**: Pista Green & Royal Off-White

---

## 🚀 Running the Website

```bash
npm start
```
Open your browser at:
```
http://localhost:3000
```
Or open [`index.html`](index.html) directly in any web browser!

---

## 🎨 Design & Features

1. **Envelope Intro Overlay**:
   - Royal forest green envelope with wax seal split animation
   - Custom Arabic calligraphy for `ا ر` (Alif & Ra) and `A & R`
   - Arabic seal inscription: `أكبر · رضوانة · ٢٠٢٦`
   - "Tap to open" interactive gesture
2. **Hero Header**:
   - Arabic Bismillah (`بِسْمِ ٱللَّٰهِ ٱلرَّحْمَٰنِ ٱلرَّحِيمِ`)
   - Animated character-by-character names blur reveal for **AKBAR & RISWANA**
   - Arabic names & letters display: `أكبر · رضوانة (ا & ر)`
   - Location & date: `Andathode, Thrissur · 17 October 2026`
3. **Smooth Scroll & Micro-Interactions**:
   - Lenis smooth scrolling with GSAP ScrollTrigger
   - Interactive pistachio and white petal explosion on tap/click
   - Mobile motion shake detection triggering floral bursts
   - Mobile falling ambient petals
4. **The Nikah Ceremony**:
   - 3D perspective date flip: `17.10.2026`
   - Typewriter venue reveal for `V. P. MAMU COMMUNITY HALL, ANDATHODE — THRISSUR, KERALA`
   - Direct Google Maps navigation button
5. **Live Countdown Clock**:
   - Real-time days, hours, minutes, seconds flip odometer
   - Automatically handles post-event message (*"Alhamdulillah — the Nikah is complete ♥"*)
6. **Closing Du'a & Calendar**:
   - Sunnah Islamic du'a:
     > بَارَكَ ٱللَّٰهُ لَكُمَا وَبَارَكَ عَلَيْكُمَا وَجَمَعَ بَيْنَكُمَا فِي خَيْرٍ
     > *(May Allah bless you, and shower His blessings upon you, and join you together in goodness.)*
   - Direct Google Calendar template and Apple `.ics` integration
   - Venue map link button
7. **Ambient Background Nasheed**:
   - Audio track (`noor-ul-nikah.mp3`) with gentle 4-second volume fade-in
   - Floating music player with animated 4-bar equalizer
