ALGORITHM GMC_ALGO_ASSG //start the algorithm

// declare variables to be used
VAR
    char_counter, word_counter, vowel_counter, i, space_counter : INTEGER :=0
    sentence: STRING

    // begin execution
BEGIN
    Read(sentence)  // receive sentence

// loop through all letters in the sentence 
WHILE (i < sentence.length) DO
    
    // check if indexed character is a space and increment space_counter variable if it is a space, else increment char_counter
    IF (sentence[i] = " ") THEN
        space_counter := space_counter + 1
    ELSE 
        char_counter := char_counter + 1
    END_IF

    // check if indexed character is a vowel
    SWITCH (sentence[i]) DO
        case "a" : vowel_counter := vowel_counter + 1; BREAK;
        case "e" : vowel_counter := vowel_counter + 1; BREAK;
        case "i" : vowel_counter := vowel_counter + 1; BREAK;
        case "o" : vowel_counter := vowel_counter + 1; BREAK;
        case "u" : vowel_counter := vowel_counter + 1; BREAK;
        default : vowel_counter
    END_SWITCH

    i := i + 1
END_WHILE

word_counter := word_counter + 1

write (word_counter)
write (char_counter)
write (vowel_counter)