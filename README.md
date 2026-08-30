# CW Morse QSO cheat sheet

Useful tips and notes for performing amateur radio CW Morse QSOs, compiled by Norbert HA2NON.

## Additional characters

These need to be known besides standard letters and numbers:

| Character | Morse code |
|-----------|------------|
| `?`       | ..--..     |
| `/`       | -..-.      |
| `-`       | -....-     |

Sending at least 8 dits in a row or a few separate `E` letters indicates that you made an error and will resend.

Sending two `E` letters (dits) after a QSO is finished is a common way to say goodbye.

### Characters used mostly in ragchew QSOs

| Character | Morse code     |
|-----------|----------------|
| `.`       | .-.-.-         |
| `,`       | --..--         |

## CQ call variations

| Call      | Meaning                                                | Example                   |
|-----------|--------------------------------------------------------|---------------------------|
| `CQ`      | Calling any station                                    | `CQ CQ CQ DE HA2NON K`    |
| `CQ DX`   | Calling long-distance / intercontinental stations only | `CQ DX CQ DX DE HA2NON K` |
| `CQ POTA` | Calling as a Parks on the Air activator                | `CQ POTA DE HA2NON K`     |
| `CQ SOTA` | Calling as a Summits on the Air activator              | `CQ SOTA DE HA2NON K`     |
| `CQ TEST` | Calling in a contest (short for *CONTEST*)             | `CQ TEST DE HA2NON K`     |
| `CQ FD`   | Calling during Field Day                               | `CQ FD DE HA2NON K`       |

## Things used at the beginning/end of messages

| Code    | Meaning                       | Where to use            | Example                   |
|---------|-------------------------------|-------------------------|---------------------------|
| `K`     | Waiting for callers           | At the end of a CQ call | `CQ CQ CQ DE FROM FROM K` |
| `KN`    | Waiting for a specific caller | At the end of a message | `TO DE FROM KN`           |
| `SK`    | Closing the QSO               | At the end of a QSO     | `TO DE FROM SK`           |
| `SK CL` | Closing the QSO with QRT      | At the end of a QSO     | `TO DE FROM SK CL`        |

## Prosigns (Procedural Signals)

The characters of prosigns need to be transmitted without any space between them.

| Prosign    | Meaning                                                           | Where to use                                                              |
|------------|-------------------------------------------------------------------|---------------------------------------------------------------------------|
| `<BK>`     | Break                                                             | Send instead of the header and footer `TO DE FROM` part of a message      |
| `<BT>` (=) | Separate message parts or a filler to indicate sender is thinking | Between RST, Name, and QTH sections, or while thinking about what to send |
| `<AS>`     | Please wait, I'll be back soon                                    | When the sender needs to leave the QSO for a short time                   |
| `<AR>` (+) | End of message / back to you                                      | `TO DE FROM AR KN` or before the message footer `AR TO DE FROM KN`        |

`BK` can also be used to break into an ongoing QSO. Break can be accepted with `GA` (go ahead).
Note that if QSO participants are using `KN` at the end of each period then you might not want to break into the conversation with `BK`.

## Q codes

Useful codes to know:

| Code   | Meaning                    | When it is used                                                                           |
|--------|----------------------------|-------------------------------------------------------------------------------------------|
| `QRL?` | Is the frequency clear?    | Checking if the frequency is clear before transmitting                                    |
| `QRZ?` | Who is calling me?         | Caller's callsign was not heard completely, or when seeking callers                       |
| `QTH`  | Location                   | Giving or asking for station location (e.g., `QTH BUDAKESZI`)                             |
| `QSL`  | Acknowledgment of receipt  | Acknowledging message receipt or confirming contact (e.g., `QSL VIA LOTW`)                |
| `QSO`  | Two-way radio contact      | General communication / contact (e.g., `TNX FER QSO`)                                     |
| `QRS`  | Slow down                  | Requesting the sender to reduce sending speed                                             |
| `QRV`  | Ready to receive / operate | Asking or stating readiness (e.g., `QRV?` or `HR QRV`)                                    |
| `QRT`  | Shutting down              | Ending operation, turning off the radio                                                   |
| `QRX`  | Stand by / wait            | Asking the other station to wait specified number of minutes (e.g., `QRX 5`)              |
| `QRU`  | Have you anything for me?  | Stating nothing further to send (e.g., `QRU 73`) or asking if more info is needed         |
| `QSY`  | Change frequency           | Changing frequency (e.g., `QSY DN 2` [2 kHz] or `QSY 7.030`)                              |
| `QSX`  | Listening on frequency     | Used in split DX operation (e.g., `QSX 7.025` or `QSX UP 2`)                              |
| `QRP`  | Low power operation        | Indicating low-power operation ($\le 5\text{W}$, e.g., `RIG QRP 5W`)                      |
| `QRO`  | High power operation       | Indicating high power (e.g., `PWR 500W QRO`) or requesting increased power (`PSE QRO`)    |
| `QSK`  | Break-in operation         | Indicating full break-in CW capability (e.g., `RIG IS QSK`)                               |
| `QRM`  | Man-made interference      | Indicating man-made interference (e.g., `SRI QRM ON FREQ`)                                |
| `QRN`  | Natural interference       | Indicating atmospheric / natural noise (e.g., `QRN ON FREQ`)                              |
| `QSB`  | Fading signal              | Indicating that the signal is fading (e.g., `UR SIG HAS QSB`)                             |
| `QRG`  | Exact frequency            | Telling or asking for exact frequency (e.g., `QRG?` or `UR QRG 7.025`)                    |
| `QRA`  | Station name               | Asking for or giving the name/call of station (e.g., `QRA?` or `QRA HA2NON`)              |
| `QRB`  | Distance between stations  | Asking for or giving distance (e.g., `QRB?` or `QRB ABT 500 KM`)                          |
| `QTR`  | Exact UTC time             | Asking for or giving the exact time (e.g., `QTR?` or `QTR 1845Z`)                         |
| `QSD`  | Defective keying           | Indicating faulty or bouncing keying (e.g., `UR KEYING IS QSD`)                           |
| `QSZ`  | Send each word twice       | Asking or stating to send each word/group twice (e.g., `PSE QSZ`)                         |
| `QSP`  | Relay message              | Asking or agreeing to relay to another station (e.g., `PSE QSP TO DL1ABC`)                |

## Abbreviations used in messages

| Abbreviation  | Meaning                                                 |
|---------------|---------------------------------------------------------|
| `CQ`          | Calling any station ("seek you")                        |
| `DE`          | From / this is                                          |
| `UR`          | Your                                                    |
| `MY`          | My                                                      |
| `U`           | You                                                     |
| `HR`          | Here                                                    |
| `FER`         | For                                                     |
| `TU`          | Thank you                                               |
| `TNX`         | Thanks                                                  |
| `R`           | Roger, explicitly confirms solid copy (*)               |
| `CFM`         | Confirm / confirmed                                     |
| `RST`         | Signal report                                           |
| `5NN`         | 599 signal report                                       |
| `SIG`         | Signal                                                  |
| `HW CPI?`     | How do you copy?                                        |
| `HW?`         | How copy? (short form)                                  |
| `CPI` / `CPY` | Copy                                                    |
| `PSE`         | Please                                                  |
| `AGN` / `AGN?`| Again / message needs to be repeated                    |
| `RPT`         | Repeat / report                                         |
| `SRI`         | Sorry                                                   |
| `FB`          | Fine business (great, excellent)                        |
| `GUD`         | Good                                                    |
| `VY`          | Very                                                    |
| `ES`          | And                                                     |
| `TT`          | That                                                    |
| `NW`          | Now (e.g., `NW QRZ?`, `NW 5NN`)                         |
| `ABT`         | About (e.g., `PWR ABT 100W`, `WX ABT 20C`)              |
| `C`           | Correct / yes                                           |
| `B4`          | Before (e.g., `WKD B4`)                                 |
| `NIL`         | Nothing / nothing heard                                 |
| `GM`          | Good morning                                            |
| `GA`          | Good afternoon or go ahead (response to a `BK` breakin) |
| `GE`          | Good evening                                            |
| `GD`          | Good day                                                |
| `GN`          | Good night                                              |
| `GL`          | Good luck                                               |
| `44`          | Common greeting in POTA / SOTA QSOs                     |
| `73`          | Best regards                                            |
| `72`          | Best regards (common in QRP operation)                  |
| `88`          | Love and kisses                                         |
| `99`          | Keep out / get lost (blunt/unfriendly)                  |
| `HPE`         | Hope                                                    |
| `CUAGN`       | See you again                                           |
| `CUL` / `CU`  | See you later / see you                                 |
| `BCNU`        | Be seeing you                                           |
| `WKD` / `WRK` | Worked / working (e.g., `NICE TO WRK U`)                |
| `OP`          | Operator                                                |
| `NAME`        | Operator name                                           |
| `OM` / `OB`   | Old man / old boy (male operator)                       |
| `YL`          | Young lady (female operator)                            |
| `XYL`         | Wife                                                    |
| `DR`          | Dear                                                    |
| `OT`          | Old timer (experienced operator)                        |
| `HI`          | Laughter in Morse                                       |
| `LID`         | Poor / impolite operator                                |
| `LOC`         | Maidenhead grid locator (e.g., `LOC JN97`)              |
| `GRID`        | Grid square locator                                     |
| `CONDX`       | Band / propagation conditions                           |
| `WX`          | Weather                                                 |
| `TEMP`        | Temperature                                             |
| `DEG`         | Degrees                                                 |
| `DX`          | Long distance / foreign station                         |
| `RIG`         | Radio equipment                                         |
| `TRX`         | Transceiver                                             |
| `TX`          | Transmitter                                             |
| `RX`          | Receiver                                                |
| `PWR`         | Power                                                   |
| `ANT`         | Antenna                                                 |
| `DIPOLE`      | Dipole antenna                                          |
| `VERT`        | Vertical antenna                                        |
| `BEAM` / `YAGI`| Directional beam / Yagi antenna                        |
| `LW`          | Long wire antenna                                       |
| `LOOP`        | Loop antenna                                            |
| `GND`         | Ground / earth                                          |
| `KEY`         | Straight key                                            |
| `PADDLE`      | Keyer paddle                                            |
| `BUG`         | Semi-automatic mechanical key                           |
| `NR`          | Number                                                  |
| `REF`         | Reference identifier (POTA / SOTA, e.g., `REF HU-0001`) |
| `EXCH`        | Contest exchange                                        |
| `STN`         | Station                                                 |
| `BURO`        | QSL Bureau (e.g., `QSL VIA BURO`)                       |
| `LOTW`        | Logbook of The World confirmation                       |
| `DIR`         | Direct QSL via mail                                     |
| `UP`          | Listen up / higher frequency (split)                    |
| `DN`          | Down / listen down frequency (split)                    |
| `GG`          | Going                                                   |
| `CL`          | Closing station / going off air                         |

(*) If you missed something (e.g., the operator's name), do not send `R`.
Send `BK` followed by your request: `BK TNX = UR 599 = OP AGN PSE? BK`

## RST signal reports

Signal reports consist of 3 digits: **R**eadability (1–5), **S**ignal strength (1–9), and **T**one (1–9).

| Component           | Scale  | Meaning                                                                 |
|---------------------|--------|-------------------------------------------------------------------------|
| **R** (Readability) | 1 to 5 | 1 = Unreadable, 3 = Readable with difficulty, 5 = Perfectly readable    |
| **S** (Strength)    | 1 to 9 | 1 = Barely perceptible, 5 = Fairly good, 9 = Extremely strong           |
| **T** (Tone)        | 1 to 9 | 1 = Very rough AC, 5 = Filtered rectified AC, 9 = Pure crystal DC note  |

With modern transceivers, the Tone report is almost always `9` (pure DC note), so signal reports in CW typically end in `9` (e.g., `599`, `579`, `449`).

## Cut numbers

In fast exchanges, contests, and signal reports, numbers with long Morse patterns are often abbreviated with single letters:

| Cut letter | Digit | Morse code | Common examples                                     |
|------------|-------|------------|-----------------------------------------------------|
| `T`        | 0     | `-`        | `1TT W` = `100 W`                                   |
| `A`        | 1     | `.-`       | Contest serial numbers (e.g., `ANN` = `199`)        |
| `U`        | 2     | `..-`      | Contest serial numbers                              |
| `V`        | 3     | `...-`     | Contest serial numbers                              |
| `4`        | 4     | `....-`    | (Rarely cut)                                        |
| `E`        | 5     | `.`        | Contest exchanges (e.g., `ENN` = `599`)             |
| `6`        | 6     | `-....`    | (Rarely cut)                                        |
| `B`        | 7     | `-...`     | Contest serial numbers                              |
| `D`        | 8     | `-..`      | Contest serial numbers                              |
| `N`        | 9     | `-.`       | `5NN` = `599` (most common)                         |

`T`, `A`, `E`, and `N` are by far the most widely used cut numbers in everyday CW operation.

## Typical weather (WX) descriptions

Common weather expressions in ragchew QSOs:

| Expression            | Meaning      |
|-----------------------|--------------|
| `WX SUNNY TEMP 25C`   | Sunny, 25°C  |
| `WX CLR TEMP 18C`     | Clear, 18°C  |
| `WX CLOUDY TEMP 15C`  | Cloudy, 15°C |
| `WX RAIN TEMP 10C`    | Rainy, 10°C  |
| `WX SNOW TEMP -2C`    | Snow, -2°C   |

## Requesting repeats

When parts of a transmission are missed:

| Code            | Meaning                            |
|-----------------|------------------------------------|
| `AGN PSE`       | Please send again                  |
| `OP?` / `NAME?` | What is your name?                 |
| `QTH?`          | What is your location?             |
| `RST?`          | What is my signal report?          |
| `AA <word>`     | Send all after `<word>`            |
| `AB <word>`     | Send all before `<word>`           |
| `BN <w1> <w2>`  | Send all between `<w1>` and `<w2>` |
| `WA <word>`     | Send word after `<word>`           |
| `WB <word>`     | Send word before `<word>`          |

### Handling partial callsigns

When multiple stations respond at once, or when only part of a callsign is copied:

| Scenario                   | What you send | What caller replies     |
|----------------------------|---------------|-------------------------|
| Copied suffix only (`CD`)  | `?CD 5NN BK`  | `AB1CD AB1CD 5NN BK`    |
| Copied prefix only (`AB1`) | `AB1? 5NN BK` | `AB1CD AB1CD 5NN BK`    |
| Too much QRM / pileup      | `QRZ?`        | All stations call again |

### Split operation (DX pileups)

In heavy pileups (especially DXpeditions or rare DX stations), the DX station transmits on one frequency and listens slightly higher or lower to keep their calling frequency clear:

| Code / Phrase     | Meaning                                        | Example                      |
|-------------------|------------------------------------------------|------------------------------|
| `UP` / `UP 1`     | Listening 1 kHz (or higher) above TX frequency | `CQ DX DE 3B8/HA2NON UP 1 K` |
| `UP 2-5`          | Listening in a 2 to 5 kHz spread above         | `3B8/HA2NON UP 2/5 K`        |
| `DN` / `DN 1`     | Listening 1 kHz below TX frequency             | `3B8/HA2NON DN 1 K`          |
| `QSX <freq>`      | Listening on a specific frequency              | `3B8/HA2NON QSX 7.025 K`     |

## Operational tips

* **Check before transmitting**: Always listen for a moment, then send `QRL?` and listen again before calling CQ on an apparently clear frequency. If someone responds with `C`, `R`, or `QRL`, move to a different frequency.
* **Zero-beating / CW pitch**: When answering a CQ, align your transmit frequency with the other station by matching their audio pitch to your transceiver's CW sidetone pitch (typically 500–700 Hz) so you fall directly inside their receiver passband.
* **Use RIT instead of VFO**: If a calling station answers slightly off-frequency, adjust your receiver with RIT (Receiver Incremental Tuning / Clarifier) instead of moving your main VFO. Moving your main VFO changes your transmit frequency and causes both stations to chase each other across the band.
* **Match sending speed**: When answering a CQ, send at or slightly below the calling station's speed. If a station sends `QRS`, reduce your speed immediately.
* **Keep exchanges concise in pileups**: When working DX, POTA, or SOTA activators, keep transmissions minimal (e.g., callsign once, signal report + `TU`) to help keep the frequency flowing.

## Example QSOs

### Fast / POTA QSO

| From     | Message                      |
|----------|------------------------------|
| `HA2NON` | `CQ POTA DE HA2NON HA2NON K` |
| `AB1CD`  | `AB1CD`                      |
| `HA2NON` | `AB1CD 5NN BK`               |
| `AB1CD`  | `BK 5NN TU 73`               |
| `HA2NON` | `TU HA2NON QRZ?`             |

### Short QSO

| From     | Message                             |
|----------|-------------------------------------|
| `HA2NON` | `CQ CQ CQ DE HA2NON HA2NON K`       |
| `AB1CD`  | `AB1CD`                             |
| `HA2NON` | `AB1CD DE HA2NON UR RST 599 5NN BK` |
| `AB1CD`  | `BK UR RST 599 5NN BK`              |
| `HA2NON` | `BK TU ES 73 DE HA2NON SK`          |
| `AB1CD`  | `BK TNX 73 HA2NON DE AB1CD SK E E`  |
| `HA2NON` | `E E`                               |

### Longer QSOs

#### Casual

| From     | Message                                                                                                              |
|----------|----------------------------------------------------------------------------------------------------------------------|
| `HA2NON` | `CQ CQ CQ DE HA2NON HA2NON K`                                                                                        |
| `AB1CD`  | `HA2NON DE AB1CD AB1CD K`                                                                                            |
| `HA2NON` | `BK GA TNX FER CALL = UR RST 599 5NN = OP NORBERT NORBERT = QTH BUDAKESZI BUDAKESZI = HW? BK`                        |
| `AB1CD`  | `R R GA NORBERT TNX FB = UR RST 579 579 = OP JOHN JOHN = QTH LONDON LONDON = HW? BK`                                 |
| `HA2NON` | `BK TNX FER QSO 73 ES CUAGN SK AB1CD DE HA2NON KN`                                                                   |
| `AB1CD`  | `BK R TNX 73 HA2NON DE AB1CD SK E E`                                                                                 |
| `HA2NON` | `E E`                                                                                                                |

#### Traditional

| From     | Message                                                                                                                          |
|----------|----------------------------------------------------------------------------------------------------------------------------------|
| `HA2NON` | `CQ CQ CQ DE HA2NON HA2NON K`                                                                                                    |
| `AB1CD`  | `HA2NON DE AB1CD AB1CD KN`                                                                                                       |
| `HA2NON` | `AB1CD DE HA2NON GA TNX FER CALL = UR RST 599 5NN = OP NORBERT NORBERT = QTH BUDAKESZI BUDAKESZI = HW? AR AB1CD DE HA2NON KN`    |
| `AB1CD`  | `HA2NON DE AB1CD GA NORBERT TNX FB = UR RST 579 579 = OP JOHN JOHN = QTH LONDON LONDON = HW? AR HA2NON DE AB1CD KN`              |
| `HA2NON` | `AB1CD DE HA2NON TNX FER QSO 73 ES CUAGN SK AB1CD DE HA2NON KN`                                                                  |
| `AB1CD`  | `HA2NON DE AB1CD TNX 73 SK E E`                                                                                                  |
| `HA2NON` | `E E`                                                                                                                            |
