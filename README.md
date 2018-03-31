# SwiftDateToZodiac
Swift Date to Zodiac sign converter 

## How to use

1.  Import `ZodiacSign.swift` to your project
2.  Get `zodiac` property

<pre>
let date = Date()
print(date.zodiac)

let sign = timePicker.date.zodiac
print(sign)
</pre>

Output will be like:

<pre>
Aquarius
</pre>

If you need covert sign to String, use:

<pre>
let signString = String(describing: date.zodiac)
</pre>
