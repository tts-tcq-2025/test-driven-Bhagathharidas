Test Case Description	               Input String	                           Expected Output / Exception Message                             Notes 
Empty string returns0	                     ""	                                       0                                                        Validates base case
Single number	                             "5"                                       5                                                        Validates single number input
Two numbers, comma delimiter	            "1,2"	                                     3                                                         Validate the sum of two numbers.
Multiple numbers, comma delimiter	       "1,2,3,4,5"	                               15                                                         Validate the sum of five numbers.
New lines between numbers	                "1\n2,3"	                                  6                                                         Validate the output as 6 for the input.
Custom single-character delimiter	        "//;\n1;2"	                                3                                                         Validate the delimiter with any following length and multi character.
Custom multi-character delimiter	         "//[***]\n1***2***3"                     	6                                                          Validate the delimiter with any following length and multi character.
Negative number throws exception	          "1,-2,3"	                                Exception: negatives not allowed: -2                       Validate the negative numbers.           
Multiple negatives in input	                "1,-2,-3,4"                              	Exception: negatives not allowed: -2, -3                   Validate the negative numbers.    
Numbers greater than 1000 are ignored	      "2,1001"	                                2                                                          Validate Numbers bigger than 1000 should be ignored  
Custom delimiter, numbers > 1000 ignored	 "//[***]\n1***1000***1001"	               1001                                                         ValidateCustom delimiter, numbers > 1000 ignored
Only delimiters, no numbers	                "//;\n"	                                   0                                                          Validate the empty string 
Delimiter of any length                    	"//[abc]\n1abc2abc3"	                     6                                                          Validate the delimiter with any following length.
Input with invalid delimiter usage (not supported)	"1,\n"	                           Not supported / undefined behavior                         Verify following input is NOT ok:
