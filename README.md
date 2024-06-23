# Project Title
Bitcoin

# Solidity
A simple ERC-20 token contract Written in Solidity for creating and managing tokens on a Blockchain.
REQUIREMENTS
    1. Your contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
    2. Your contract will have a mapping of addresses to balances (address => uint)
    3. You will have a mint function that takes two parameters: an address and a value. 
       The function then increases the total supply by that number and increases the balance 
       of the “sender” address by that amount
    4. Your contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. 
       It will take an address and value just like the mint functions. It will then deduct the value from the total supply 
       and from the balance of the “sender”.
    5. Lastly, your burn function should have conditionals to make sure the balance of "sender" is greater than or equal 
       to the amount that is supposed to be burned.

# Description
Bitcoin is a basic implementation of an ERC-20 token contract ,allowing users to mint and burn tokens.The contract stores token balances in a mapping and updates the total supply accordingly.This contract can be used as a starting point for more complex token implementations.

# Author
Vemula Narendra 
