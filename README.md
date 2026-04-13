# DynamicArray.sol
DynamicArray.sol
pragma solidity ^0.8.20;
contract DynamicArray {
    uint[] public numbers;

    function push(uint value) public {
        numbers.push(value);
    }
}
