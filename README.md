class Solution:
    def createTargetArray(self, nums: List[int], index: List[int]) -> List[int]:
        x = []
        for i , j in zip(nums,index):
            x.insert(j,i)
        return x
