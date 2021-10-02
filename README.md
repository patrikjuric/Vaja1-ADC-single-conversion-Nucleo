# Vaja1-ADC-single-conversion-Nucleo

Zelena LED je priključena na PA5 pin, MODRA pa ni priključena nikamor saj je ploščica Nucleo sploh nima. Na PIN PA0 je priključen potenciometer. Razvojna ploščica ima 3 ADC razdelke. Izbrani ADC pretvornik(i) imajo oznako s trikotnikom, to pomeni da so te pini že zasedeni, da to omejitev razrešimo moravmo vse zasedne pine, ki so uporabljeni v ADC pretvorbi postaviti v stanje RESET. Imamo 15 vhodnih kanalov, na 16 pa lahko izvajamo le Single-ended pretvorbo. Poleg pina PA0 se izpiše ADC_IN5.Izbrana ločljivost je 8bit-na torej je območje vrednosti od 0 ÷ 255. Ostale možne ločljivosti pretvorbe  so še 
a.	10bit ,od 0 do 1023,
b.	12bit, od 0 do 4095,
c.	14bit, od 0 do 16383.


Komentar na delovanje:
Kodo sva v šoli preizkusila in bila je brez kakršnihkoli Errorjev, ampak ko sva jo poskušala naložiti na ploščico Nucleo je javilo napako "No ST Link Detected" in nama onemogočilo da bi program naložila na najino ploščico zato na videoposnetku ni vidnega delovanja ampak je lepo razvidno da nalaganje ni bilo mogoče.
