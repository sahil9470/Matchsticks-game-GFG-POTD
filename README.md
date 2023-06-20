# Matchsticks-game-GFG-POTD
Today I'm discussing about gfg problem Matchsticks game cpp

class Solution {
  public:
    int matchGame(long long N) {
        // code here
        return N%5?N%5:-1;
    }
};
