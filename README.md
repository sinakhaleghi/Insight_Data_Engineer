@Author Sina Khaleghi

## Run:
use this command to run the code: ./run.sh

## Method:
1) reading the given input files
2) for each hour, the actual and predicted stock prices are stored, and the error values are determined for the stocks that match in both files. 
3) a sliding window technique is used in the approach (deque). the values are then stored in the deque, and once the values for a new hour is computed, the first value in the queue is popped, and the new one is queued.
4) the final average error is computed by averaging over the values in the window and written to the output once each average error is computed.