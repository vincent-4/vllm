(engine-args)=

# Engine Arguments

vLLM's engine arguments are organized into several categories to make navigation and configuration easier. Below are the available arguments for each category:

## Model Configuration

Arguments related to model loading, tokenization, and model-specific settings:

<!--- pyml disable-num-lines 7 no-space-in-emphasis -->
```{eval-rst}
.. argparse::
    :module: vllm.engine.arg_utils
    :func: _engine_args_parser
    :prog: vllm serve
    :nodefaultconst:
    :group: Model Configuration
```

## KV Cache Configuration

Arguments for controlling the KV cache behavior:

<!--- pyml disable-num-lines 7 no-space-in-emphasis -->
```{eval-rst}
.. argparse::
    :module: vllm.engine.arg_utils
    :func: _engine_args_parser
    :prog: vllm serve
    :nodefaultconst:
    :group: KV Cache Configuration
```

## Scheduler Configuration

Arguments for controlling request batching and scheduling:

<!--- pyml disable-num-lines 7 no-space-in-emphasis -->
```{eval-rst}
.. argparse::
    :module: vllm.engine.arg_utils
    :func: _engine_args_parser
    :prog: vllm serve
    :nodefaultconst:
    :group: Scheduler Configuration
```

## Parallelism Configuration

Arguments for controlling tensor and pipeline parallelism:

<!--- pyml disable-num-lines 7 no-space-in-emphasis -->
```{eval-rst}
.. argparse::
    :module: vllm.engine.arg_utils
    :func: _engine_args_parser
    :prog: vllm serve
    :nodefaultconst:
    :group: Parallelism Configuration
```

## LoRA Configuration

Arguments for LoRA adapter support:

<!--- pyml disable-num-lines 7 no-space-in-emphasis -->
```{eval-rst}
.. argparse::
    :module: vllm.engine.arg_utils
    :func: _engine_args_parser
    :prog: vllm serve
    :nodefaultconst:
    :group: LoRA Configuration
```

## Speculative Decoding Configuration

Arguments for speculative decoding:

<!--- pyml disable-num-lines 7 no-space-in-emphasis -->
```{eval-rst}
.. argparse::
    :module: vllm.engine.arg_utils
    :func: _engine_args_parser
    :prog: vllm serve
    :nodefaultconst:
    :group: Speculative Decoding Configuration
```

## Quantization Configuration

Arguments for model quantization:

<!--- pyml disable-num-lines 7 no-space-in-emphasis -->
```{eval-rst}
.. argparse::
    :module: vllm.engine.arg_utils
    :func: _engine_args_parser
    :prog: vllm serve
    :nodefaultconst:
    :group: Quantization Configuration
```

## Decoding Configuration

Arguments for controlling token generation and decoding:

<!--- pyml disable-num-lines 7 no-space-in-emphasis -->
```{eval-rst}
.. argparse::
    :module: vllm.engine.arg_utils
    :func: _engine_args_parser
    :prog: vllm serve
    :nodefaultconst:
    :group: Decoding Configuration
```

## Multimodal Configuration

Arguments for multimodal inputs:

<!--- pyml disable-num-lines 7 no-space-in-emphasis -->
```{eval-rst}
.. argparse::
    :module: vllm.engine.arg_utils
    :func: _engine_args_parser
    :prog: vllm serve
    :nodefaultconst:
    :group: Multimodal Configuration
```

## Observability Configuration

Arguments for metrics, logging, and monitoring:

<!--- pyml disable-num-lines 7 no-space-in-emphasis -->
```{eval-rst}
.. argparse::
    :module: vllm.engine.arg_utils
    :func: _engine_args_parser
    :prog: vllm serve
    :nodefaultconst:
    :group: Observability Configuration
```

## Prompt Adapter Configuration

Arguments for prompt adapters:

<!--- pyml disable-num-lines 7 no-space-in-emphasis -->
```{eval-rst}
.. argparse::
    :module: vllm.engine.arg_utils
    :func: _engine_args_parser
    :prog: vllm serve
    :nodefaultconst:
    :group: Prompt Adapter Configuration
```

## Other Configuration

Other miscellaneous arguments:

<!--- pyml disable-num-lines 7 no-space-in-emphasis -->
```{eval-rst}
.. argparse::
    :module: vllm.engine.arg_utils
    :func: _engine_args_parser
    :prog: vllm serve
    :nodefaultconst:
    :group: Other Configuration
```

## Async Engine Arguments

Below are the additional arguments related to the asynchronous engine:

<!--- pyml disable-num-lines 7 no-space-in-emphasis -->
```{eval-rst}
.. argparse::
    :module: vllm.engine.arg_utils
    :func: _async_engine_args_parser
    :prog: vllm serve
    :nodefaultconst:
```
