:hover - ელემენტს ეძლევა სტილი, როცა მომხმარებელი მასზე მაუსს ატარებს.
მაგ: button:hover { background-color: blue; }

:focus - ელემენტს ეძლევა სტილი, როცა მასზე ფოკუსი არის (მაგალითად, როცა ფორმის ველში დაწკაპავთ ან ტაბით შეხვალ).
მაგ: input:focus { border-color: red; }

:active - ელემენტს ეძლევა სტილი, როცა ის აქტიურია (მაგალითად, როცა ღილაკზე დააწკაპებთ).
მაგ: button:active { background-color: green; }

:nth-child(n) - შეარჩევს n პოზიციაზე მდგომ შვილ ელემენტს (მეოთხე, მეხუთე და ა.შ
მაგ: li:nth-child(2) { color: red; }

:first-child - პირველად შვილ ელემენტს ანიჭებს სტილს.
მაგ: p:first-child { font-weight: bold; }

:last-child - უკანასკნელ შვილ ელემენტს ანიჭებს სტილს.
მაგ: p:last-child { color: blue; }

:nth-of-type(n) - n პოზიციაზე არსებულ ერთნაირი ტიპის (მაგალითად, მხოლოდ p ტეგები) ელემენტებს ანიჭებს სტილს.
მაგ: p:nth-of-type(3) { font-size: 20px; }

:checked - შეარჩევს მონიშნულ ელემენტებს (მაგალითად, მონიშნული checkbox ან radio).
მაგ: input:checked { border-color: green; }

:disabled - დაობლებული ელემენტებისთვის გამოიყენება.
მაგ: button:disabled { background-color: grey; }

:not(selector) - შერჩევს იმ ელემენტებს, რომლებიც არ ემთხვევიან selector-ს.
მაგ: div:not(.active) { opacity: 0.5; }

ფსევდო-ელემენტები საშუალებას გაძლევს, დაამატო სტილები ან ელემენტები არსებული ელემენტის შიგნით, მისი კოდის რედაქტირების გარეშე.

::before - ელემენტამდე შეაქმნევინებს შინაარსს ან სტილს.
მაგ: h1::before { content: "★ "; color: gold; }

::after - ელემენტის შემდეგი შეაქმნევინებს შინაარსს ან სტილს.
მაგ: h1::after { content: " ★"; color: gold; }

::first-letter - შერჩევს ტექსტის პირველ ასოს და მისცემს სტილს.
მაგ: p::first-letter { font-size: 30px; color: red; }

::first-line - ტექსტის პირველ ხაზს მისცემს სტილს.
მაგ: p::first-line { font-weight: bold; }

::selection - შერჩევს ტექსტს, რომელსაც მომხმარებელი მარკავს და მისცემს სტილს.
მაგ: p::selection { background-color: yellow; }

::placeholder - ინფუტის ფლეისჰოდერს გასტილავს და იმოქმედებს ზედ;