# Prompt Gemini — veicoli davanti ai monumenti (golf cart e Fiat)

> ⚠️ Solo **social e shot list**. Su GYG/Airbnb solo foto vere (rifiuto/sospensione + recensioni
> "foto false"). Regola d'oro: mettere il mezzo **solo dove può davvero fermarsi**. Niente Trevi,
> Pantheon, Navona, Piazza di Spagna, Piazza del Popolo: pedonali → foto falsa e rischio multa.

## Come usarli
1. Parti da una foto **vera** del mezzo, meglio di 3/4 o di lato, alla stessa altezza d'occhio.
2. Incolla il **template** + **lo sfondo** scelto dalla lista.
3. Una foto alla volta. Se viene male, usa le correzioni in fondo.

## Template (incollare sempre)
```
Keep the vehicle exactly as it is in this photo: same model, color, roof, seats, wheels, logos and license plate, same size and camera angle. Keep any people exactly as they are. Replace only the background with: [BACKGROUND].
The vehicle is parked legally on the road, at a realistic distance from the monument, with the monument clearly recognizable behind it. Match perspective and horizon to the original photo. Light: [LIGHT]. Make the shadows under the vehicle and on the people match the new light direction. Photorealistic, like an iPhone photo, natural colors, no text, no logos added, no watermark, no other vehicles in front of the subject.
```

## Sfondi (sostituisci [BACKGROUND] e [LIGHT])

| # | Monumento | [BACKGROUND] | [LIGHT] | Mezzo / prodotto |
|---|---|---|---|---|
| 1 | Colosseo | the Colosseum seen from the Colle Oppio viewpoint on Via Nicola Salvi, the full curved facade filling the frame, a stone wall and oleanders on the left | warm late-afternoon sun from the right | tutti |
| 2 | Colosseo di notte | the Colosseum illuminated at night with warm golden arches, deep blue sky, cobblestones in the foreground | night, warm light from the monument | golf cart notte |
| 3 | Circo Massimo | the long grassy Circus Maximus with the ruins of the Palatine Hill rising behind, umbrella pines and cypresses | golden-hour sun from behind the camera | Fiat gialla / golf cart |
| 4 | Altare della Patria | the white marble Altar of the Fatherland on Piazza Venezia, bronze winged statues against the sky | soft morning light | golf cart giorno |
| 5 | San Pietro | the dome of St. Peter's Basilica at the end of Via della Conciliazione, seen from Piazza Pio XII | early-morning light, sun from the left | Jolly / golf cart |
| 6 | Castel Sant'Angelo | Castel Sant'Angelo and the Bridge of Angels with its statues, seen from the Lungotevere road | golden hour, warm reflections on the Tiber | Jolly / golf cart |
| 7 | Gianicolo | the panoramic terrace of the Janiculum Hill with the domes and rooftops of Rome below, a stone balustrade | sunset, orange sky | Jolly / golf cart |
| 8 | Fontanone | the monumental Fontana dell'Acqua Paola on the Janiculum Hill, white travertine arches, water pouring into the basin | warm morning light | golf cart fontane |
| 9 | Bocca della Verità | the portico of Santa Maria in Cosmedin with its Romanesque bell tower and the round Temple of Hercules nearby | soft afternoon light | Jolly (Vacanze Romane) |
| 10 | Cavalieri di Malta | Piazza dei Cavalieri di Malta on the Aventine, white walls with obelisks and cypresses, the famous keyhole gate | late afternoon, sun through the cypresses | Fiat gialla |
| 11 | Pincio | the Pincio terrace road beside Casina Valadier, umbrella pines, Rome's skyline and St. Peter's dome in the distance | golden hour | golf cart (è la loro base reale) |
| 12 | Via Appia | the ancient Appian Way with Roman paving stones, umbrella pines and ancient tomb ruins along the road | warm morning light | Fiat gialla |
| 13 | Coppedè | the fairy-tale Art Nouveau palaces of Quartiere Coppedè around the Fountain of the Frogs | soft morning light | Fiat gialla "Like a Roman" |

## Generare da zero (senza foto di partenza) — solo moodboard
```
Photorealistic travel photo: a [VEHICLE: e.g. sunshine-yellow 1960s Fiat 600 convertible with the roof down / white electric sightseeing golf cart with a white roof and clear roll-up side curtains], parked on the road in front of [MONUMENT DESCRIPTION]. A professional Italian driver in a navy polo at the wheel and [GUESTS] smiling in the passenger seats, candid moment. [LIGHT]. Shot on iPhone, natural colors, no text, no logos.
```
Il mezzo generato da zero NON sarà identico a quello vero: usarlo solo per idee/inquadrature.

## Correzioni
- Monumento sbagliato/inventato: `The monument is not accurate. Make it look exactly like the real [MONUMENT] in Rome.`
- Mezzo cambiato: `You changed the vehicle. Restore it exactly as in the original photo.`
- Mezzo "incollato": `The vehicle looks pasted. Match its lighting, shadows and perspective to the new background.`
- Prospettiva: `The vehicle and the background have different horizons. Align the horizon and camera height.`
