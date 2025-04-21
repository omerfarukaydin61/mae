python main_pretrain.py \
    --batch_size 64 \
    --model mae_vit_large_patch16 \
    --mask_ratio 0.75 \
    --epochs 300 \
    --warmup_epochs 40 \
    --blr 1.5e-4 --weight_decay 0.05 \
    --data_path ../DATA/dataset