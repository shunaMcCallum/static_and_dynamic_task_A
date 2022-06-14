### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:


  def check_for_ace(self, card):
    if card.value = 1:  # the operator should be ==
      return True
    else # colon required after else
      return False
  

  dif highest_card(self, card1 card2): # should say def instead of dif, and comma missing between card1 and card2
  if card1.value > card2.value: # if statement should be indented one step over to the right
    return card # should say card1 instead of card
  else:
    return card2
  


def cards_total(self, cards): # indentation - whole method should be indented one step over to the right
  total # total should be set equal to 0 when declared
  for card in cards:
    total += card.value
    return "You have a total of" + total # indentation - return statement should be outside of the for loop
    #  total also needs to be concatenated into the return statement using f and {}
  
```
