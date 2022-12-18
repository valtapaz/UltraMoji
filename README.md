# UltraMoji Font
A fan-made font for the writing system of the Land of Light

## Basis
The alphabet of M-78, known as ウルトラ文字 or UltraMoji, is based phonetically on Japanese (which usually has a consonant component and a vowel component for each character), but its writing system splits the Japanese Kana into English-compatible symbols, making English use also possible. I wasn't able to find any fonts based on this language, so I decided to make my own.

(Below image for reference; image copyright Tsuburaya Productions)
![The Ultra alphabet](https://m-78.jp/wp-content/uploads/2021/07/%E3%82%A6%E3%83%AB%E3%83%88%E3%83%A9%E6%96%87%E5%AD%97.jpg =500)

Since Japanese does not include certain Roman letters (such as L or V), this font comes in two variants: 
 - M-78 Inochi, which uses self-made approximations of what these letters may look like. Most of these are preexisting letters with the same kinds of Dakuten (") or Handakuten (°) that separates the UltraMoji (and Japanese) letters T and D, although X had to be more custom, combining a K and an S into one symbol. 
 - M-78 Seigi, which drops any non-Japanese letters, save reusing the K symbol for C. 

In UltraMoji, direct vowels (i.e. ones that are not preceded by a consonant) have a symbol that exists neither in English nor in Japanese; I have assigned that symbol to the forward slash for now (/), but in the future I would like to integrate it into the OTF features listed below.

## OTF Notes
While releasing as a TTF would be more universally compatible, some Japanese elements retained by UltraMoji made it unfeasible without a more complex format. The OTF font allows for the following features: 
 - "N": Japanese/UltraMoji has two uses for this letter: one as a consonant, and one when next to a vowel. The OTF will default to the consonant N, but will automatically change it to the with-vowel form when vowels (including Y, as it's closer to a vowel in English than in Japanese)
 - "W": this character interacts with other characters differently, with each UltraMoji vowel component placed inside of the consonant one rather than next to it. The OTF uses a consonant-only form of W by default, but will automatically replace a W followed by a vowel (again, including Y) with this form. I do not know whether the intent was to place all letters, consonant or vowel, inside the W character, so consonants are not included here, although I might later add the letter H in this ruleset given how frequently it appears next to W in English. 

## Misc
To my knowledge, UltraMoji does not include numbers, so I included some Ultra signatures in lieu of them. Numbers 1-9 represent the nine Showa Ultra Brothers from Zoffy　to 80, while the number 0 is, well… Zero. (Part of me wanted to take the joke further and put Seven and 80 under 7 and 8, but that would just jumble and confuse the rest of the content.)

Regarding uses, the LICENSE file goes into more detail, but basically: If you are working with Tsuburaya Productions officially and would like to use this font in any official capacity, I would love it if you did so, but I'd ask that you let me know in advance (you can reach out to me on Twitter via @MxylValtapaz). Beyond that, this font should not be used for commercial purposes by businesses unaffiliated with Tsuburaya Productions. 
