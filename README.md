# Dokumentacja: Dodawanie nowych timerów

##  Gdzie dodawać timer

Wszystkie timery znajdują się w tablicy:

```js
const timers = [
  {
    title: "Opis timera",
    date: new Date(ROK, MIESIĄC, DZIEŃ, GODZINA, MINUTA, SEKUNDA)
  }
];
```

##  Jak poprawnie dodać timer

### Przykład:
Chcesz ustawić datę:
> 15 marca 2026, godzina 14:30:00

### Poprawny zapis:
```js
{
  title: "Od jakiegoś wydarzenia minęło:",
  date: new Date(2026, 2, 15, 14, 30, 0)
}
```
### Uwaga! JavaScript liczy miesiące od **0 do 11**, a nie od 1 do 12!

