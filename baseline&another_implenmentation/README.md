this contation all baselines!
and another implementation about tree hirarchical attention network. what difference is that use another method to represent the trees!

use baseline_train to run baseline mode ,and let arg.method=average/attention/sum/

use train to run tree model, arg.attention=False:average model, else: tree attention model.

THAN.py #217 is softmax.but it's not really need, because F.cross_entropy contain softmax. if use it will cause bad performance.
