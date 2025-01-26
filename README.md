# Assignment_BTECH2026_-2301921529011-DSAclass Solution {
Problem Statement : (Two Sum) Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.
                     You may assume that each input would have exactly one solution, and you may not use the same element twice. You can return the answer in any order.
                     Example: Input: nums = [3,3] ; target = 6 ; Output: [0,1]


Coding Platform Used : Leet Code 

Approach (Brute Force)                     
                     
    public class Main {
    public static void main(String[] args) {
        int arr[]= {3,3};
        int sum = arr[0]+arr[1];
        int target = sum; 
        System.out.println(target);
    }
}
