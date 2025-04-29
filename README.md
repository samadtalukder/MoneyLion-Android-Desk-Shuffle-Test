# MoneyLion Android Desk Shuffler Test

## Question Description
Create an app to display a grid of 6 cards, referred to as dealt cards, and a horizontally scrollable set of 8 cards, referred to as the deck, as shown below.

## Functionality Requirements

The app should have the following functionalities:

- Shuffle the dealt cards randomly when the SHUFFLE button is clicked. 
- Swap a dealt card with a card from the deck by tapping on the dealt and deck cards to swap.
Example: 
- If the second dealt card is tapped and then the first deck card is tapped, the second card from dealt cards must be swapped with the first card from the deck. 
- If a selected dealt card is tapped again, it must be unselected.

The project already has boilerplate code to create the required Ul according to the functionality specified. 
Connect the dots and code the missing pieces for the app to work as described above.

The classes needing code completion: MainActivity.kt. DeckAdapter.kt, and DealtCardsAdapter.kt, are open in the editor by default. 
Complete the code in the following methods and lines where comments are written:

```sh
setupListeners() [MainActivity.kt]: Write code to shuffle the dealt cards and update the grid in the UI.
```

```sh
setupDealtCards() [MainActivity.kt]: Write code to attach the adapter to the dealtCards GridView and update the selected card in the dealtCards using the position provided by the OnltemClickListener callback.
```

```sh
setupDeck() [MainActivity.kt]: Write code to attach the adapter to the deck RecyclerView.
```

```sh
swapDealtCardWithDeckCard(deckPosition: Int) [MainActivity.kt]: Write code to swap the selected card in the dealtCards with the selected card from the deck.
```

```sh
bindImageAndSetListener(binding: DeckItemBinding, position: Int, drawableld: Int) [DeckAdapter.kt]: Write code to bind the image to the ViewHolder and invoke the itemTapListener when any item is tapped.
```
## Demo