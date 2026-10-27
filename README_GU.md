# Palak Parlour — શરૂઆતનું પ્રોજેક્ટ (ગુજરાતી)

આ એક પ્રારંભિક મોબાઇલ-ફ્રેન્ડલી વેબ-એપ/PWA છે. તેમાં દૂધ, દહીં, છાશના ડેમો પ્રોડક્ટ, કાર્ટ, ગ્રાહક વિગતો, WhatsApp ઓર્ડર મેસેજ અને UPI intent linkનું મૂળભૂત માળખું છે.

## સૌથી પહેલાં બદલો
`app.js` ખોલો:
- `SHOP_WHATSAPP = "91XXXXXXXXXX"` ને તમારા દુકાનના WhatsApp નંબરથી બદલો (ભારત માટે 91 + 10 અંક; + અથવા સ્પેસ ન લખો).
- `SHOP_UPI_ID = ""` માં તમારો સાચો UPI ID મૂકો, ઉદાહરણ `yourname@upi`. કોઈ UPI PIN, બેંક પાસવર્ડ અથવા OTP ક્યારેય કોડમાં ન લખો.
- `products` માં ભાવ અને પેકિંગ તમારા વાસ્તવિક ભાવ મુજબ બદલો.

## Android મોબાઈલમાં ટેસ્ટ કરવાની સરળ રીત
1. ZIP ફાઇલ Extract કરો.
2. GitHub account બનાવો અને નવું public અથવા private repository બનાવો.
3. આ ફાઇલો repositoryમાં Upload files દ્વારા અપલોડ કરો.
4. Repository Settings → Pages → Deploy from a branch → `main` → `/ (root)` પસંદ કરો.
5. પ્રકાશિત થયેલી HTTPS વેબસાઇટ લિંક ખોલીને ઓર્ડર અને મોબાઇલ ડિસ્પ્લે ચકાસો. GitHub Pages માટે account/repositoryની ઉપલબ્ધતા અને settings લાગુ પડે છે.
6. ગ્રાહક Android Chromeમાં વેબસાઇટ ખોલે → ત્રણ ડોટ → Add to Home screen / Install app પસંદ કરી શકે છે (બ્રાઉઝર પ્રમાણે વિકલ્પ બદલાય).

## ખૂબ જરૂરી મર્યાદાઓ
- આ હજુ Google Play Storeમાં અપલોડ કરવા માટે તૈયાર native Android AAB નથી. આ PWA/web app starter છે.
- WhatsApp નંબર ઉમેર્યા વિના ઓર્ડર સીધો દુકાનને નહીં જાય.
- UPI લિંક માત્ર UPI એપ ખોલે છે; આ કોડ પેમેન્ટ ખરેખર સફળ થયું છે તે verify કરતો નથી. ચુકવણીની ખાતરી UPI એપ/બેંકમાં જાતે કરો.
- પ્રોડક્ટ ભાવ ડેમો છે; તમારા સાચા ભાવથી બદલો.
- ઓર્ડર આ નમૂનામાં કોઈ databaseમાં સંગ્રહાતા નથી. WhatsApp મારફતે જ મોકલવાનો ઉદ્દેશ છે.
- આ ફોર્મ ગ્રાહકનું નામ, ફોન અને સરનામું લે છે. ગ્રાહકોને માહિતીનો ઉપયોગ કેવી રીતે થશે તે જણાવો અને તેને જાહેર repositoryમાં ક્યારેય મૂકશો નહીં.
- Play Store માટે privacy policy, app signing, testing, Google Play Console account અને વર્તમાન Play policiesનું પાલન જરૂરી રહેશે.
